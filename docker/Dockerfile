FROM openjdk:8
MAINTAINER yuderen yuderen6312@163.com

COPY ./eureka-1.0-SNAPSHOT.jar /home/eureka.jar

WORKDIR /home

EXPOSE 9001

CMD ["java", "-jar", "eureka.jar"]