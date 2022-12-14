6장 브랜치 실습 정리(1~4)
===================
 
6.2.1 저장소 생성 및 초기화
--------------------------
브랜치 실습을 위한 환경을 구축합니다.

![1](https://user-images.githubusercontent.com/112995645/194897755-5dfc887f-93a5-4864-96b3-c077c2999c3a.PNG)


현재 브랜치가 main이라는 것을 확인할 수 있습니다.

<br/>

6.2.2 기본 브랜치
----------------
모든 커밋과 이력은 브랜치에 기록됩니다.

저장소를 처음 초기화하면 main 브랜치 하나가 자동으로 생성됩니다.

![2](https://user-images.githubusercontent.com/112995645/194897765-0a6b1d99-2e1e-4602-a4f0-20f6a0be5d8e.PNG)

git status 명령어의 출력 결과 메시지에서 "ON branch main"을 확인할 수 있습니다.

깃에서 항상 현재 작업하는 브랜치 위치를 확인하는 것이 중요합니다.

![3](https://user-images.githubusercontent.com/112995645/194897776-f257ff0a-6ccb-49e7-938a-61185d8b5c0e.PNG)

또는 branch 명령어로 현재 브랜치를 확인할 수 있습니다.

<br/>

6.3.1 브랜치 생성 
----------------
브랜치는 깃에서 또 하나의 개발 분기점을 의미합니다.

새로운 개발 분기점이 필요할 때는 브랜치를 추가로 생성할 수 있습니다.

브랜치 생성 명령어 - $ git branch 브랜치이름 커밋 ID

![4](https://user-images.githubusercontent.com/112995645/194914431-bd796c04-0cbc-49bd-bdec-927900153e36.png)

<br/>

6.3.2 브랜치 이름
----------------
브랜치 작업은 알기 쉬운 이름으로 짓는 것이 좋습니다.

주의할 점은 브랜치 이름은 중복해서 사용하지 않아야 한다는 것입니다.

![5](https://user-images.githubusercontent.com/112995645/194897800-49fb7a5c-3ffc-40b6-b2b5-31eecb29af48.PNG)

이미 생성된 브랜치 이름과 동일한 이름으로 생성한다면 오류가 발생합니다.

<br/>

6.4.1 간단 브랜치 목록
---------------------
branch 명령어는 단독으로도 실행할 수 있습니다.

![6](https://user-images.githubusercontent.com/112995645/194897809-2cbb211b-48b0-4200-a1cd-aa8e93121c14.PNG)

git branch 명령어를 실행하면 현재 모든 브랜치가 나열됩니다.

별표(*)는 현재 선택된 브랜치를 의미합니다.

<br/>

6.4.2 브랜치 해시
----------------
브랜치는 특정한 커밋의 해시 값(SHA1)을 가리킵니다.

$ git rev-parse 브랜치이름

![7](https://user-images.githubusercontent.com/112995645/194897827-51ad1b8a-4535-4d5a-b74e-aab1afdce987.PNG)

먼저 커밋 로그를 확인합니다.

![8](https://user-images.githubusercontent.com/112995645/194897836-14306180-21e2-406c-92df-bc8e5009ee47.PNG)

이번에는 커밋 해시(SHA1)을 확인합니다.

브랜치의 해시 값과 커밋의 값이 동일한 것을 확인할 수 있습니다.

<br/>

6.4.3 브랜치 세부 사항 확인
-------------------------
branch 명령어 뒤에 -v 또는 -verbose 옵션을 함께 사용하면

브랜치 이름, 커밋ID, 커밋 메시지를 같이 볼 수 있습니다.

![9](https://user-images.githubusercontent.com/112995645/194897847-adeca78d-e72c-4785-a0bf-339b5170b4c3.PNG)




