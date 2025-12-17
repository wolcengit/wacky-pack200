# wacky-pack200
Due to the legacy project, Pack200 and Upack00 needed to be used under Java 17, so the relevant source code was extracted from src.zip of jdk8 to form this project.

# maven

```xml
<dependency>
    <groupId>wacky-pack200</groupId>
    <artifactId>wacky-pack200</artifactId>
    <version>1.0.0</version>
</dependency>
```

```java
// java17+
import wacky.java.util.jar.Pack200;
```