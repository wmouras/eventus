# Getting Started

### Reference Documentation

For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.1.0/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.1.0/maven-plugin/reference/html/#build-image)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/docs/3.1.0/reference/htmlsingle/#using.devtools)
* [Spring Session](https://docs.spring.io/spring-session/reference/)
* [Spring Data MongoDB](https://docs.spring.io/spring-boot/docs/3.1.0/reference/htmlsingle/#data.nosql.mongodb)
* [Spring Boot Actuator](https://docs.spring.io/spring-boot/docs/3.1.0/reference/htmlsingle/#actuator)
* [Docker Compose Support](https://docs.spring.io/spring-boot/docs/3.1.0/reference/htmlsingle/#features.docker-compose)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.1.0/reference/htmlsingle/#web)
* [Spring Configuration Processor](https://docs.spring.io/spring-boot/docs/3.1.0/reference/htmlsingle/#appendix.configuration-metadata.annotation-processor)
* [Rest Repositories](https://docs.spring.io/spring-boot/docs/3.1.0/reference/htmlsingle/#howto.data-access.exposing-spring-data-repositories-as-rest)
* [OAuth2 Client](https://docs.spring.io/spring-boot/docs/3.1.0/reference/htmlsingle/#web.security.oauth2.client)
* [Spring Security](https://docs.spring.io/spring-boot/docs/3.1.0/reference/htmlsingle/#web.security)
* [Jersey](https://docs.spring.io/spring-boot/docs/3.1.0/reference/htmlsingle/#web.servlet.jersey)

### Guides

The following guides illustrate how to use some features concretely:

* [Accessing Data with MongoDB](https://spring.io/guides/gs/accessing-data-mongodb/)
* [Building a RESTful Web Service with Spring Boot Actuator](https://spring.io/guides/gs/actuator-service/)
* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)
* [Accessing JPA Data with REST](https://spring.io/guides/gs/accessing-data-rest/)
* [Accessing Neo4j Data with REST](https://spring.io/guides/gs/accessing-neo4j-data-rest/)
* [Accessing MongoDB Data with REST](https://spring.io/guides/gs/accessing-mongodb-data-rest/)
* [Securing a Web Application](https://spring.io/guides/gs/securing-web/)
* [Spring Boot and OAuth2](https://spring.io/guides/tutorials/spring-boot-oauth2/)
* [Authenticating a User with LDAP](https://spring.io/guides/gs/authenticating-ldap/)

### Docker Compose support

This project contains a Docker Compose file named `compose.yaml`.
In this file, the following services have been defined:

* mariadb: [`mariadb:latest`](https://hub.docker.com/_/mariadb)
* mongodb: [`mongo:latest`](https://hub.docker.com/_/mongo)

Please review the tags of the used images and set them to the same as you're running in production.

