# 🗺️ 거긴 위허맵! - 경북대학교 건물 별 인구 밀집도 및 위험도 예측 서비스
> ### **콩토리 팀**
> #### 컴퓨터학부 4학년 땅콩(이예진), 컴퓨터학부 4학년 도토리(곽유진)

시연영상 -
<a href="https://youtu.be/eAaZ9AcyIqc">https://youtu.be/eAaZ9AcyIqc</a><br>
콩토리팀 웹 구현용 깃헙 -
<a href="https://github.com/yejin9989/kongtori_web.git">https://github.com/yejin9989/kongtori_web.git</a><br>
노션(협업용 툴) 링크 -
<a href="https://milkymoon.notion.site/380b78020f1442269d2da91af206422b">https://milkymoon.notion.site/380b78020f1442269d2da91af206422b</a><br>
~~~java
public class 시연_영상 {
  public static void main(String[] args) {
    System.out.println("https://youtu.be/eAaZ9AcyIqc");
  }
}
~~~
~~~java
public class 노션_링크 {
  public static void main(String[] args) {
    System.out.println("https://milkymoon.notion.site/380b78020f1442269d2da91af206422b");
  }
}
~~~
~~~java
public class 콩토리_웹_깃헙 {
  public static void main(String[] args) {
    System.out.println("https://github.com/yejin9989/kongtori_web.git");
  }
}
~~~
***

#### 경북대학교 컴퓨터학부 해커톤 -
### *" COVID-19로 변화된 대학 생활을 개선할 수 있는 창의적이고 혁신적인 소프트웨어 자유 개발 "*

<br>
<img width="773" alt="설문조사1번문항" src="https://user-images.githubusercontent.com/52647838/126686556-674a9d29-0c6e-4c5f-a7cf-dcd9bf0cf8ac.png">
<img width="774" alt="설문조사2번문항" src="https://user-images.githubusercontent.com/52647838/126686724-2a8c0503-835e-48bc-960c-74cb06df4078.png">
<img width="772" alt="설문조사3번문항" src="https://user-images.githubusercontent.com/52647838/126686731-4fbe7fba-628d-4ff7-be8a-e943d57b9486.png">


> **&#128173; 질문1**: 시험 기간이지만 코로나 때문에 학교 시설물을 이용하기 꺼려지셨나요?

> **&#128173; 질문2**: 식사 시간에 어디에서 밥을 먹어야 할지 고민되셨나요?

> **&#128173; 질문3**: 학교에서 저렴하게 운동시설을 이용하고 싶은데 어느 시간대에 사람이 적을지 궁금하셨나요?
<br>


## &#128161; 콩토리의 거긴 위허맵!	&#128161;</dt>
### - 경북대학교 건물 별 인구 밀집도 및 위험도 예측 서비스</dd>
<img width="300" alt="스플래시" src="https://user-images.githubusercontent.com/31399012/126704213-a77c3ec6-240c-45ec-8ce2-c4064bdb67b1.gif">

교내 헬스장을 등록은 했는데 연이어 들려오는 헬스장 확진자 소식..<br>
공대식당 치즈날치알밥을 먹고싶은데 사람이 많을까봐, 코로나가 걱정되어 오늘도 햇반에 계란후라이를 먹습니다.<br>
자취방에서는 왠지 의자도 불편하고 집중이 잘 안되지만 IT4호관에 들어가기 전 까지 사람이 많을지 적을지 알 수 없습니다.<br>
집에서 출발하기 전에 어느 건물에 얼마나 많은 사람이 있는지 알 수 있다면 어떨까요?<br><br>
### &#128171; 그렇다면 이제, 콩토리 팀의 *거긴 위허맵!* 을 사용할 때입니다!! &#128171;<br><br>
> &#128204; 미리 혼잡도 및 위험도를 예측해 ***자발적으로 거리두기 및 코로나 감염 예방 실현 효과***<br>
> &#128204; 시험기간 강의실이나 열람실, 식사시간 교내식당, 운동시간 체육시설 등 인파가 몰리는 시간대에 ***인구 분산 효과***<br>

### 어떻게요?
경북대학교 학생이라면 출입하기 위해 늘 찍는 <b>QR코드</b>를 활용해서 만들어보았습니다!<br>
우리는 학교 시설물을 이용할 때마다 QR코드로 출입 기록을 남기지만,<br>
그 데이터가 어디로 가는지 궁금해하지도 않았고 정확히 아는 사람도 없었으며<br>
마이데이터이지만 본인이 활용할 수 있는 방법이 없었습니다.<br><br>
*이미 구축 된 인프라를 활용하여 경제성과 편리함을 동시에 챙깁니다. 이용자 또한 번거롭게 다른 절차를 밟을 필요가 없습니다.*<br><br>

- 예상(평균)체류시간 경북대학교 학부생들을 대상으로 한 설문조사를 바탕으로 위험도를 계산하였습니다.
<img width="772" alt="설문조사4번문항" src="https://user-images.githubusercontent.com/52647838/126689536-3e1c7ac3-6c82-4ac5-862f-43a51408ce68.png">
<img width="772" alt="설문조사5번문항" src="https://user-images.githubusercontent.com/52647838/126689547-f9e22769-dc80-4796-afea-a42b9b2b50a3.png">
<img width="772" alt="설문조사6번문항" src="https://user-images.githubusercontent.com/52647838/126689557-bb544570-e092-4bde-b7e0-42d2aef69ca4.png">

- 수학과 + 통계학과 학부생의 자문을 받아 위험도를 계산하였습니다.<br>
    → 전문가의 자문을 구하여 더욱 더 정확한 위험도 계산이 가능합니다.<br>
    → 데이터가 많이 모이면 모일수록 AI를 학습시켜 더욱더 정확한 위험도와 밀집도 예측이 가능해질 것입니다.<br>
    <img width="254" alt="ScreenShot4" src="https://user-images.githubusercontent.com/52647838/126736064-de2a7900-0fc0-4347-92dd-e44d7141a383.png">

- 크누피아의 QR코드 출입내역 데이터 담당하는 외부 업체와 실제로 계약 또는 실제 데이터를 제공받아 더욱더 정확한 정보 제공이 가능해질 것입니다.
 <br>
 
***

### 기능 소개
1. 순수하게 경북대학교 지도로서 활용 가능
2. 실시간 학교 시설물별 인구 밀집도 및 위험도 예측 및 정보 제공 기능
3. 학교 시설물별 평균적인 인구 밀집도 및 위험도 정보 제공 기능
4. 지도 내 검색 기능
5. 내 위치 기반 서비스 
<img width="429" alt="ScreenShot1" src="https://user-images.githubusercontent.com/52647838/126701392-b716918e-26be-4d42-ad84-83e4b203b210.png">
<img width="429" alt="ScreenShot2" src="https://user-images.githubusercontent.com/52647838/126701399-4ac82fec-142d-45b1-8000-53c344ff143d.png">
<img width="429" alt="ScreenShot3" src="https://user-images.githubusercontent.com/52647838/126701406-02cbb59c-d98b-4c73-9705-fc9fa45d52e6.png">

### 장점
1. 기존에 사용하는 QR코드 시스템을 이용해 경제성과 편리성을 높임
2. 이용자 또한 번거롭게 다른 절차를 밟을 필요가 없음
3. 웹-앱 모두 사용 가능해 편리함
4. DB에서 실시간으로 위험 예측도 정보를 제공받음
5. 이용자 스스로 건강을 지킬 수 있음

### 기대 효과
1. 자발적 거리두기
2. 코로나 감염 스스로 예방 효과
3. 인구 분산 효과
4. 지역사회 감염 최소화에 기여
5. 코로나 이후에도 용이하게 사용 가능(학헬, 도서관, 공식 등)

### 발전 가능성
1. 데이터가 쌓이면 쌓일수록 더욱더 정확해지는 위험도 예측!
2. (주)에스원과의 계약 또는 정보 제공을 통한 정확한 정보 제공!
3. 교내 확진자 수 및 동선 안내 기능 추가 예정!

***
<br>

## 콩토리의 거긴 위허맵! 사용 방법 두가지 &#10071; &#10071;

***현재 학생들의 QR코드 출입 데이터는*** <br>
***https://www.somoonhouse.com/kongtori/_access_automation.jsp 에서 자동, 랜덤으로 생성해주고 있습니다.*** <br>
***위험도 또한 현재 시간을 기준으로 인구 밀집도 및 위험도를 계산하므로,*** <br>
***먼저 [링크](https://www.somoonhouse.com/kongtori/_access_automation.jsp) 로 이동해 랜덤 데이터를 생성해주세요.***<br>
+ 안드로이드용 apk 사용
  1. https://github.com/yejin9989/kongtori/tree/master/app/release 의 [app-release.apk](https://github.com/yejin9989/kongtori/tree/master/app/release) 를 다운받는다.
  2. 안드로이드 핸드폰이나 에뮬레이터에서 거긴 위허맵을 설치한다.
+ web으로 접속
  1. https://www.somoonhouse.com/kongtori/map.jsp 로 접속해 기능을 살펴본다.



<br><br><br>

##	&#128583; 읽어주셔서 감사합니다! 	&#128583;


