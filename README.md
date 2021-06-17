## Santander Dev Week - Back-end ♨️
[![java-badge][java-img]][java] [![postgre-badge][postgre-img]][postgre]

[java-img]: https://img.shields.io/badge/Java-v8-orange
[java]: https://www.java.com/pt-BR/download/

[postgre-img]: https://img.shields.io/badge/PostgreSQL-database-blue
[postgre]: https://www.postgresql.org/

## Descrição 📌
Criando endpoints(GET, POST, PUT, DELETE) em uma API de stocks do Santander utilizando Java na IDE [IntelliJ](https://www.jetbrains.com/pt-br/idea/) e a image do PostgreSQL dentro de um container no Docker.

## Execução ✅
Acesse a seguinte URL pra entrar na página da API de cotações: 
**`https://bootcamp-dio-santnder.herokuapp.com/bootcamp/swagger-ui/index.html?configUrl=/bootcamp/v3/api-docs/swagger-config#/`**


### Endpoints da API: 
* __GET/stock/{id}__ -> Seleciona o stock do ID inserido.
* __GET/stock/today__ -> Seleciona todos os stocks inseridos no dia
* __GET/stock__ -> Retorna todos os stocks cadastrados no banco
* __POST/stock__ -> Cadastra um novo stock
* __PUT/stock__ -> Edita um stock já cadastrado
* __DELETE/stock__ -> Apaga um stock

![image](https://user-images.githubusercontent.com/61299540/122330552-c3b4e680-cf09-11eb-907b-ed2589dd1cdc.png)
