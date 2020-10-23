FROM 10.100.1.204:31104/unis/java:8

ADD ./target/eureka-server.jar /root
CMD ["sh", "-c", "cd /root; java -Djava.security.egd=file:/dev/./urandom -jar /root/eureka-server.jar --eureka-server.server.enable-self-preservation=false"]
EXPOSE 9001

