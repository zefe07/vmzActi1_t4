# Actividad 1 T4 - Spring Boot en AWS

Este es un proyecto backend desarrollado con **Spring Boot** como parte de la Actividad 1 de la Fase 3. El proyecto fue probado localmente y posteriormente desplegado en un servidor VPS (AWS EC2).

## Tecnologías utilizadas
*   Java 17
*   Spring Boot 3
*   Maven
*   AWS EC2 (Ubuntu Linux)

## Endpoints disponibles
El proyecto cuenta con 2 controladores y 3 endpoints en total:
1.  `/autor` - Devuelve el nombre del desarrollador.
2.  `/materias` - Devuelve una lista simulada de materias.
3.  `/info` - Devuelve información adicional del proyecto.

## Despliegue
El proyecto se compiló en un archivo `.jar` y se ejecutó en el servidor VPS utilizando el puerto **8081** con el comando `nohup` para mantenerlo en segundo plano.

**Enlace del proyecto corriendo en el VPS:** 
[http://77.113.100.81:8081/autor]
[http://77.113.100.81:8081/materias]
[http://77.113.100.81:8081/mis-datos]

## Repositorio

[https://github.com/zefe07/vmzActi1_t4]