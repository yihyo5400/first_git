# first_git
======

## Git < Pull-Request >

- 공동의 git -> fork    
- 내 repo name 하단에 공동의 git 주소 확인    
- 내 repo에서 clone (내 repo git 주소)     
	;clone 할 경우 자동 생성	-> git init & git remote add origin (내 repo git 주소)    
- git remote add upstream (공통의 repo git 주소)    
	; upstream 이라는 branch 생성    		
//remote는 작업 전후 순서 무관    
//upstream branch 생성한 이유 ; 충돌시 pull 후 충동 해결하기 위해    
- 작업 후 add-commit -> push 할 경우 branch명을 유의해야함    
	; push 내 repo에  해주어야함 //내 repo로 push해서 pull-request 하는 순서    
	git push origin master - > pull-request    
  
  * * *

## pull-request 충돌 해결    
 - git pull upstream master (공통 작업을 수정해야함)    
 - 충돌 해결 후     
	작업 후 add-commit -> push 할 경우 branch명을 유의해야함    
		; push 내 repo에  해주어야함     
		git push origin master - > pull-request    
    
    
  * * *

## 명령어    
- ls : 파일 list    
- ls - a : 숨겨진 파일 list까지 모두    
- cd : 상위 폴더로 이동    
- pwd : 현재 작업 경로    
- git remote –v     
- git branch : 현재 어떤 branch 위치하는지    

## Branch
	; 현재 작업 중인 파일이 아닌 현재 작업과 동일한 내용의 가지를 쳐 본래 작업에 	merge    
//본 작업을 건들지 않고 수정사항을 확인해볼 수 있음    
//merge -> 본 작업에 수정한 사항을 업데이트    
