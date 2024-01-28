# RisingCamp4

## 아이스크림 타이쿤 게임 제작
### 시연영상 링크
https://drive.google.com/file/d/1QTxxZQ--IL7MuEnpreyc5rgOFNn7UJGA/view?usp=sharing

### 게임 소개
#### 손님의 주문에 따라 아이스크림을 만들어 판매
### 게임 구성
#### 1. 시작화면
###### - 시작 버튼(OPEN)을 누르면 게임 화면으로 넘어감
###### - 타이쿤 게임을 한 횟수만큼 날짜가 증가하여 캘린더에 표시됨
![image](https://github.com/yerim425/RisingCamp4/assets/111108212/bbc2133d-b8e5-454a-abf9-33ac90076e7d)
#### 2. 게임 화면
##### 2.1 게임 시간 : 2분(끝나면 자동으로 결과 화면으로 넘어감)
##### 2.2 아이스크림 제작 
###### - 최대 2단까지 쌓을 수 있음
###### - 콘을 터치하여 준비해야 아이스크림 터치 가능
###### - 아이스크림 제작 후 손님을 터치하면 손님에게 전달됨
###### - 휴지통을 터치하면 아이스크림 다시 제작 가능(재료비는 증가)
##### 2.3 손님
###### - 1~5초 중 랜덤으로 비어있는 자리에 손님 채워짐
###### - 주문 아이스크림은 랜덤으로 표시(5가지 맛 중 하나, 1또는 2단으로 설정)
###### - 손님 등장 후 5초가 지나면 무표정으로 변화
###### - 5초 후 3초를 더 기다리면 화난 표정으로 변화 후 사라짐
###### - 손님 등장 후 8초 안에 아이스크림을 전달하면 기쁨 표정으로 변화 후 사라짐
##### 2.4 비용 계산
###### - 1단 아이스크림 가격 : 10 coin
###### - 2단 아이스크림 가격 : 15 coin
###### - 아이스크림 한 덩이 재료비 : 3 coin
###### - 아이스크림 콘 재료비 : 1 coin
###### - 아이스크림 제작 실수 보상 비용 : 3 coin
![image](https://github.com/yerim425/RisingCamp4/assets/111108212/903111d2-a9cb-40b1-a70f-5fdecfec5c68)
#### 3. 결과 화면
###### - 오늘의 수익이 계산되어 표시됨
###### - SharedPreference를 통해 현재까지의 총 수익에 오늘의 수익이 더해지고 저장됨
###### - 확인 버튼을 누르면 시작 화면으로 넘어감
![image](https://github.com/yerim425/RisingCamp4/assets/111108212/b275973a-a610-40ac-aee1-02a649ba1bcd)


