# first git

깃허브 사용법을 연습합니다.

READ ME는 소스에 대한 간단한 소개글을 작성합니다.

여기서는 READ ME 작성법에 대해 써봅니다.

#### 마크다운 문법

1. '#'의 갯수(1~6개)를 달리하여 글자 크기를 조정할 수 있습니다.(많을수록 작게)

   

2. 한 줄을 건너띄고 글을 써야 문장이 이어지지 않고
다음 줄로 변경되어 보여집니다.

   (e.g. 라인7~라인8에 글을 쓰면 한 줄로 보여짐.

   라인7, 라인9에 글을 쓰면 줄바꿈되어 보여짐.)



3. 가로줄 추가하기

   '---'
   ---
   '***'
   ***



4. 순서가 있는 목록 만들기
   1. 하고 엔터를 치면 자동으로 2., 3. 이 생성돼요.



5. 순서 없는 목록 만들기
   
   +, -, * 기호를 붙여서 작성하면 자동으로 글머리 기호가 생성됩니다.
   
   + "+"
   
   - "-"

   * "*"



6. 텍스트 강조하기
   
   텍스트의 일부분을 굵게 또는 기울임체로 강조

   굵게 : 텍스트 앞뒤를 ** 또는 __로 감싸기. **깃허브**

   기울임체 : 텍스트 앞뒤를 * 또는 _ 로 감싸기. *깃허브*

   굵은 기울임체 : 텍스트 앞뒤를 *** 또는 ___ 로 감싸기. ***깃허브***

   취소선 : 텍스트 앞뒤를 ~~ 로 감싸기. ~~깃허브~~



7. 소스코드 삽입하기

   소스코드를 삽입하려면 backquote(') 키를 사용

   + 한 줄 소스 코드
   
   `function add(x,y){ return x + y }`

   + 여러 줄 소스 코드

     '```' backquote 3번
     ``` python
     number = input("정수입력 : ")
     number = int(number)

     if number>0:
         print("양수입니다")
     if number<0:
         print("음수입니다")
     if number==0:
         print("0입니다")
     ```


8. 링크 삽입하기
   
   <링크주소>
   
   [링크 텍스트] (링크 주소)
