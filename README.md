# React-Study

## React?
- 리엑트란 사용자 정의 태그(컴포넌트)를 만드는 기술이다.
- 
## React 파일 (index.js, App.js ,index.html)

- `React의 중요한 파일 3가지`
   1.index.js
   2. App.js
   3. index.html  
  
```
1. index.js
src 폴더에 포함되어 있다. 메인 프로그램이라고 할 수 있다. 여기에서 HTML 템플릿 및 JavaScript의 컴포넌트를 조합하여 렌더링하고 실제 표시한다.

2. App.js
src 폴더에 있다. 이것은 컴포넌트를 정의하는 프로그램이다. 실제로 화면에 표시되는 내용 등은 여기에서 정의된다.

3. index.html
public 폴더에 있다. 메인 프로그램인 index.js에 대응되는 것으로, HTML 템플릿 파일이다. 이 파일이 직접 표시되는 것은 아니고,
index.js에 의해 일어 와서 렌더링된 결과가 표시된다. (index.html 이름을 바꿀시 오류발생)
```

## 구조
- `npm start` : index.js를 찾고 그 안에 적혀있는 내용으로 동작하는 구조


## tut-react-and-spring-data-rest
로그인 UI 방법
https://spring.io/guides/tutorials/react-and-spring-data-rest/  
```
cd ~/workspace-react
cd okreact/tut-react-and-spring-data-rest/security
npm i
./mvnw spring-boot:run
localhost:8080
```

- `공부사이트` : https://codebase.show/projects/realworld
- `샘플코드` : https://github.com/romansndlr/react-vite-realworld-example-app (react + vite)
```
<샘플코드 다운후>
cd ~/workspace-react/okreact
git clone https://github.com/romansndlr/react-vite-realworld-example-app
cd react-vite-realworld-example-app
rm -rf .git
```

- `Front public 배포사이트` : https://app.netlify.com/  (Deploy쪽 알아서 세팅해서 배포= react-vite-realworld-example-app )

## 리엑트 공부
리엑트 공부
- `배포` : https://app.netlify.com/sites/lambent-dasik-1d4e61/settings/deploys
- 
## 클래스형 vs 함수형

https://koras02.tistory.com/m/177


## Redux vs Zustand
- https://velog.io/@bluejoyq/React-Flux-%ED%8C%A8%ED%84%B4%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-Redux%EC%99%80-Zustand  
```
redux는 Action상태변경이 일어나면 store는 이전의 상태로부터 상태를 업데이트하는 reducer함수를 실행하고, 새로운 state를 저장함.
store가 변경되면 구독하는 모든 UI들에게 업데이트를 알리고, 새로 데이터 렌더링 진행.
하지만 너무나 많은 코드를 써야하고, 그 코드를 이해하는게 어려움.
redux코드를 설계하고, 코드를 구현하는데 대부분의 시간을 사용할 수 있음.

리덕스로 짯더라면 
reducers
combineReducers
Provider
userSelector
action.type 등 여러 함수들을 선언하고 써야함.
zustand는 세팅필요없이 코드짜는 로직만 집중할 수 있음.

디버깅도 devtools라는 미들웨어를 가져오면 쉽게 보고 처리 가능.
```

## URL vs URI 차이

https://velog.io/@torang/URL%EA%B3%BC-URI%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90


## 임베디드 객체안의 객체 삽입
https://jeong-pro.tistory.com/198




## jpa insert default 적용 + prePersit preXXXX 
https://dotoridev.tistory.com/6

## 기술블로그
https://velog.io/@teo


## useNavigate
Navigate를 통해서 페이지를 이동할 수 있다. 인자도 같이 넘겨서 받을 수 있음.
```
라우터 5.0 버전에서의 useHistory의 기능 중 { go, goBack, goForward }는 각각 해당 위치로, 이전으로, 다음으로 의 역할을 수행해왔는데,
이 부분도 navigate로 통일하고 index를 넣음으로써 해결
```
![image](https://user-images.githubusercontent.com/35188271/174535076-a114629c-2584-4016-8e41-07413654419b.png)
![image](https://user-images.githubusercontent.com/35188271/174535090-56c14057-ddd7-4c8a-a89f-22b58d3587e3.png)

