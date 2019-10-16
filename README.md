# Gradle
spring boot gradle로 빌드하기 예제

### post
[Gradle 빌드하기](https://paycis.tistory.com/3)

### Gradle
- 빌드도구의 한 종류. 그 외 대표적인 빌드 도구로 maven이 있다.
- Groovy언어 기반
- maven에 비해 작성과 관리가 쉬움
- 유연성, 성능 등 측면에서 maven 보다 장점을 갖고 있다. (https://gradle.org/maven-vs-gradle/)

### 빌드방법
- 명령어로 스크립트 실행하기
  - 콘솔창에서 해당 프로젝트 root 경로로 진입한 뒤  `./gradlew bootjar` 명령어 실행
- IDE에서 실행하기
  - 우측에 있는 gradle 창을 열고 `Tasks` -> `build` -> `bootJar` 더블클릭
  
### 실행하기
- 콘솔창을 열고 jar 파일이 있는 경로로 이동합니다.
- `java -jar 프로젝트명.jar` 명령어를 입력하여 스프링부트 프로젝트를 실행합니다.
