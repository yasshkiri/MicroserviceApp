
FROM openjdk:8
EXPOSE 8761

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file from the mounted volume into the container
COPY ./target /app

# Define the entry point
ENTRYPOINT ["java", "-jar", "/app/EurekaServer-0.0.1-SNAPSHOT.jar"]