# WebRTC

### 프로젝트 목적

> 웹소켓 & 미디어 접근을 이해하기 위한 프로젝트<br/>
> 개인프로젝트<br/>
> 심심풀이용

---

### 프로젝트 구조

```
RTC
├─ public
│  ├─ script.js
│  └─ style.css
├─ views
│  └─ room.ejs
├─ server.js
└─ package.json
```

---

### 파일 설명

- room.ejs: 런타임에 보여지는 화면
- script.js: 유저에게 보여지는 화면에서 동작하는 스크립트
- server.js: 웹소켓 통신을 중계하는 서버

---

### 사용한 외부 라이브러리

#### 1. socket.io

> - /socket.io/socket.io.js<br/>
>   웹소켓을 불러올 수 있는 라이브러리
>
> ```html
> <script src="/socket.io/socket.io.js"></script>
> ```

#### 2. peer.js

> - https://unpkg.com/peerjs@1.3.1/dist/peerjs.min.js<br/>
>   WebRTC를 좀 더 쉽게 사용할 수 있게 한 라이브러리
>
> ```html
> <script src="https://kit.fontawesome.com/c939d0e917.js"></script>
> ```

#### 3. fontawesome

> - https://kit.fontawesome.com/c939d0e917.js<br/>
>   폰트 및 아이콘을 사용하기 위한 라이브러리
>
> ```html
> <script src="https://unpkg.com/peerjs@1.3.1/dist/peerjs.min.js"></script>
> ```

---

### 사용 방법

1. 이름 작성 후 방 개설
2. 사람 모양 아이콘 클릭 후 URL 복사하여 연락하고 싶은 상대에게 전달
3. 전달받은 URL에 진입하여 이름 작성 후 영통 진행

---

### 구현 화면
