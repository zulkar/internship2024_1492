Test tasks.

- https://internship.jetbrains.com/projects/1501/
- https://internship.jetbrains.com/projects/1492/

Build the project to get test Jars : ./gradlew jar

Smoke TestCases:
- false: com.jetbrains.internship2024.ClassB ModuleB-1.0.jar
- true: com.jetbrains.internship2024.ClassB ModuleA-1.0.jar ModuleB-1.0.jar
- true: com.jetbrains.internship2024.ClassA ModuleA-1.0.jar
- false: com.jetbrains.internship2024.SomeAnotherClass ModuleA-1.0.jar
- true: com.jetbrains.internship2024.SomeAnotherClass ModuleA-1.0.jar commons-io-2.16.1.jar
- true: com.jetbrains.internship2024.ClassB1 ModuleB-1.0.jar