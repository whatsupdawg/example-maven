# Hello World Maven Application

A simple Hello World application built with Maven.

## Prerequisites

- [Java 11+](https://adoptium.net/)
- [Apache Maven 3.6+](https://maven.apache.org/download.cgi)

## How to Build

Clone the repository and run the following commands from the project root:

```bash
# Compile and package the application
mvn package
```

The compiled JAR will be placed in the `target/` directory.

## How to Run

```bash
java -jar target/hello-world-1.0-SNAPSHOT.jar
```

Expected output:

```
Hello, World!
```

## Project Structure

```
.
├── pom.xml
└── src
    └── main
        └── java
            └── com
                └── example
                    └── App.java
```
