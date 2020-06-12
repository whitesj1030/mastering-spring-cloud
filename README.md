https://wikibook.co.kr/mastering-spring-cloud/

# Mastering Spring Cloud
This is the code repository for [Mastering Spring Cloud](https://www.packtpub.com/application-development/mastering-spring-cloud?utm_source=github&utm_medium=repository&utm_campaign=9781788475433), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Developing, deploying, and operating cloud applications should be as easy as local applications. This should be the governing principle behind any cloud platform, library, or tool. Spring Cloud–an open-source library–makes it easy to develop JVM applications for the cloud. In this book, you will be introduced to Spring Cloud and will master its features from the application developer's point of view.
## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

All code files are present in their respective folders.
Chapters 1,3,9,13 and 14 do not contain code files. 

The code will look like the following:
```
<dependency>
  <groupId>org.springframework.cloud</groupId>
  <artifactId>spring-cloud-config-server</artifactId>
</dependency>
```

In order to successfully read through this book and work out all the code samples, we
expect readers to fulfill the following requirements:
An active internet connection
* Java 8+
* Docker
* Maven
* Git client

## Related Products
* [Spring Security - Third Edition](https://www.packtpub.com/application-development/spring-security-third-edition?utm_source=github&utm_medium=repository&utm_campaign=9781787129511)

* [Spring: Microservices with Spring Boot](https://www.packtpub.com/application-development/spring-microservices-spring-boot?utm_source=github&utm_medium=repository&utm_campaign=9781789132588)

* [Apache CloudStack Cloud Computing ](https://www.packtpub.com/virtualization-and-cloud/apache-cloudstack-cloud-computing?utm_source=github&utm_medium=repository&utm_campaign=9781782160106)

▣ 01장: 마이크로서비스 소개
마이크로서비스의 장점
스프링 프레임워크로 마이크로서비스 만들기
클라우드 네이티브 개발
마이크로서비스 아키텍처 배우기
서비스 디스커버리의 필요성 이해하기
서비스 간 통신
장애와 서킷 브레이커
요약
 
▣ 02장: 마이크로서비스를 위한 스프링
스프링 부트 소개
스프링 부트를 이용해 애플리케이션 개발하기
컨피규레이션 파일 사용자 정의하기
RESTful 웹서비스 생성하기
API 문서화
스웨거 2를 스프링 부트와 같이 사용하기
스웨거 UI를 통한 API 테스트
스프링 부트 액추에이터의 기능
애플리케이션 정보
상태 정보
매트릭스
개발자 도구
데이터베이스와 애플리케이션의 통합
예제 애플리케이션 빌드하기
애플리케이션 실행하기
요약
 
▣ 03장: 스프링 클라우드 개요
기본부터 시작하기
넷플릭스(Netflix) OSS
디스커버리와 분산 컨피규레이션
또 다른 대안 - 컨설
아파치 주키퍼
기타 프로젝트
슬루스를 사용한 분산 추적
메시징과 통합
클라우드 플랫폼 지원
다른 유용한 라이브러리
보안
테스트 자동화
클러스터 기능
프로젝트 개요
릴리즈 트레인(release trains)
요약
 
▣ 04장: 서비스 디스커버리
서버 측에서 유레카 서버 실행하기
클라이언트 측에서 유레카 활성화하기
종료 시 등록 해제
프로그램 방식으로 디스커버리 클라이언트 사용하기
고급 컨피규레이션 설정
레지스트리 갱신하기
인스턴스 식별자 변경하기
IP 주소 우선하기
응답 캐시
클라이언트와 서버 간의 보안 통신 사용하기
안전한 서비스 등록하기
유레카 API
복제와 고가용성
예제 솔루션의 아키텍처
예제 애플리케이션 개발하기
장애 조치
존(Zones)
하나의 서버를 사용하는 존
예제 애플리케이션 개발하기
요약
 
▣ 05장: 스프링 클라우드 컨피그를 사용한 분산 컨피규레이션
HTTP API 자원의 소개
네이티브 프로파일 지원
서버 측 애플리케이션 개발하기
클라이언트 측 애플리케이션 개발하기
유레카 서버 추가하기
클라이언트 측에 부트스트랩 접근 방식 사용
컨피그 서버 디스커버리
백엔드 저장소 타입
파일 시스템 백엔드
깃 백엔드
볼트 백엔드
추가 기능
시작 시 실패와 재시도
클라이언트 안전하게 하기
자동으로 컨피규레이션 다시 읽기
솔루션 아키텍처
@RefreshScope를 사용해 컨피규레이션 다시 읽기
메시지 브로커로부터 이벤트 받기
컨피그 서버에서 저장소 변경 모니터링하기
요약 109
 
▣ 6장: 마이크로서비스 간의 커뮤니케이션
다양한 커뮤니케이션 스타일
스프링 클라우드를 사용한 동기식 통신
리본을 사용한 부하 분산
리본 클라이언트를 사용해 마이크로서비스 간 커뮤니케이션하기
서비스 디스커버리와 함께 RestTemplate 사용하기
예제 애플리케이션 개발하기
페인(Feign) 클라이언트 사용하기
여러 존의 지원
애플리케이션에서 페인 사용하기
상속 지원
수동으로 클라이언트 생성하기
사용자 정의 클라이언트
요약
 
▣ 7장: 고급 부하 분산 및 서킷 브레이커
부하 분산 룰
WeightedResponseTime 룰
리본 클라이언트 사용자 정의하기
히스트릭스를 사용하는 서킷 브레이커 패턴
히스트릭스를 사용하는 애플리케이션 개발
서킷 브레이커 차단하기
대기 시간과 장애 내성 모니터링하기
히스트릭스 메트릭 스트림 노출하기
히스트릭스 대시보드
장애와 페인을 사용한 서킷 브레이커 패턴
리본을 사용해 연결 재시도하기
페인을 지원하는 히스트릭스
요약
 
▣ 08장: API 게이트웨이를 사용한 라우팅과 필터링
스프링 클라우드 넷플릭스 주울 사용하기
게이트웨이 애플리케이션 개발하기
서비스 디스커버리와 연동하기
라우트 컨피규레이션 사용자 정의하기
리본 클라이언트를 사용한 라우트 정의
종단점 관리
히스트릭스 폴백 제공하기
주울 필터
스프링 클라우드 게이트웨이 사용하기
프로젝트에 스프링 클라우드 게이트웨이 사용하기
내장된 조건자와 필터
마이크로서비스를 위한 게이트웨이
서비스 디스커버리와 통합하기
요약
 
▣ 09장: 분산 로깅과 추적
마이크로서비스를 위한 로깅의 모범 사례
스프링 부트를 사용한 로깅
ELK 스택을 사용한 통합 로그 수집
머신에 ELK 스택 컨피규레이션하기
애플리케이션과 ELK 스택 통합하기
스프링 클라우드 슬루스
슬루스와 애플리케이션 통합하기
키바나를 사용해 이벤트 찾기
집킨과 슬루스 통합하기
요약
 
▣ 10장: 추가 컨피규레이션 및 디스커버리 기능
스프링 클라우드 컨설 사용하기
컨설 에이전트 실행하기
클라이언트 측에 통합하기
서비스 디스커버리
분산 컨피규레이션
스프링 클라우드 주키퍼 사용하기
주키퍼 실행하기
서비스 디스커버리
분산 컨피규레이션
요약
 
▣ 11장: 메시지 주도 마이크로서비스
스프링 클라우드 스트림 배우기
메시징 시스템 구축하기
스프링 클라우드 스트림 사용하기
채널을 선언하고 바인딩하기
래빗엠큐 브로커를 사용해 사용자 정의 연결 설정하기
다른 스프링 클라우드 프로젝트와 통합하기
게시/구독 모델
예제 시스템 실행하기
확장 및 그루핑
컨피규레이션 옵션
스프링 클라우드 스트림 속성
속성 바인드하기
컨슈머
고급 프로그래밍 모델
메시지 생성하기
변환(transformation)
조건에 따라 메시지 소비하기
아파치 카프카 사용하기
카프카 실행하기
애플리케이션을 맞춤형으로 설정하기
카프카 스트림 API 지원
컨피규레이션 속성
다양한 바인더
요약
 
▣ 12장: API 보안 강화하기
스프링 부트에서 HTTPS 사용하기
디스커버리 보안 강화
안전한 애플리케이션 등록하기
HTTPS상에서 유레카 서비스하기
컨피규레이션 서버 보안 강화
암호화와 복호화
클라이언트와 서버를 위한 인증 구성하기
OAuth2로 권한 부여
OAuth2 소개
권한 부여 서버 구축하기
클라이언트 컨피규레이션
JDBC 백엔드 저장소 사용하기
서비스 간 권한 부여
API 게이트웨이에서 SSO 사용하기
요약
 
▣ 13장: 자바 마이크로서비스 테스팅
테스팅 전략
스프링 부트 애플리케이션 테스팅
예제 애플리케이션 개발하기
데이터베이스와 통합
단위 테스트
컴포넌트 테스트
메모리 기반 데이터베이스를 사용해 테스트 실행하기
HTTP 클라이언트와 서비스 디스커버리 다루기
예제 테스트 구현하기
통합 테스트
테스트 분류하기
HTTP 트래픽 포착하기
컨트랙트 테스트
팩트 사용하기
스프링 클라우드 컨트랙트 사용하기
성능 테스트
요약
 
▣ 14장: 도커 지원
도커 소개
도커 설치하기
자주 사용하는 도커 명령
컨테이너 시작 및 중지하기
컨테이너 목록 조회 및 제거하기
이미지 당겨오기 및 올리기
이미지 빌드하기
네트워킹
마이크로서비스의 도커 이미지 생성하기
도커 파일
컨테이너화된 마이크로서비스 실행하기
메이븐 플러그인을 사용해 이미지 빌드하기
고급 도커 이미지
지속적인 배포
도커에 젠킨스 통합하기
파이프라인 구축하기
쿠버네티스와 함께 사용하기
개념과 구성 요소
미니큐브를 통해 로컬에 쿠버네티스 실행하기
애플리케이션 배포하기
클러스터 관리하기
요약
 
▣ 15장: 클라우드 플랫폼상의 스프링 마이크로서비스
피보탈 클라우드 파운드리
사용 모델
애플리케이션 준비
히로쿠(Heroku) 플랫폼
애플리케이션 준비하기
배포 테스트하기
