FROM openjdk:17-jdk-alpine
VOLUME /tmp
COPY target/employee-api.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
