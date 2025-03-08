# Reservation Queue

실시간 예약 대기열 시스템을 구현하며 백엔드 기술을 탐구하는 사이드 프로젝트입니다. Spring Boot를 기반으로 Kafka, Redis, WebSocket 등을 활용해 확장 가능하고 효율적인 예약 시스템을 목표로 합니다.

## 1. 프로젝트 목표
- 비동기 메시지 큐(Kafka)를 이용한 대기열 처리 구현
- 실시간 알림 기능(WebSocket)으로 사용자 경험 개선
- Redis를 활용한 빠른 상태 관리와 캐싱
- 컨테이너화(Docker)를 통해 배포 자동화 연습

## 2. 개인 목표
- Java 21과 Spring Boot 3.X의 새로운 기능 탐구하기
- WebSocket과 네트워크 기초 익히기
- Kafka 공부하기

## 3. 기술 스택
- **언어**: Java 21
- **프레임워크**: Spring Boot 3.X
- **메시지 큐**: Kafka
- **캐싱**: Redis
- **실시간 통신**: WebSocket
- **배포**: Docker

## 4. 설치 및 실행
*(아직 구현 전이라 추후 업데이트 예정)*  
1. 리포지토리 클론:  
   ```bash
   git clone https://github.com/zz1996zz/reservation-queue.git
   ```
2. 의존성 설치:
   ```bash
   mvn install
   ```
3. 애플리케이션 실행:
   ```bash
   mvn spring-boot:run
   ```

## 5. 프로젝트 구조
```
src/
├── main/
│   ├── java/
│   └── resources/
└── test/
```

## 6. 진행 상황
- [X] GitHub 리포지토리 생성
- [ ] Spring Boot 초기 설정
- [ ] Kafka 연동
- [ ] WebSocket 기본 구현
- [ ] Redis 설정
- [ ] Docker 배포
