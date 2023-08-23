# git 사용방법 #
## git 설치 ##
git 홈페이지에서 git 프로그램 다운 받아 설치 <br>
(D2Coding 글꼴을 설치하여 사용하면 편리함)

## git 명령어 ##
명령어  | 기능
------------- | -------------
cd  | 디렉토리 위치 변경
pwd  | 현재 디렉토리 위치 확인
ls | 현재 디렉토리에 존재하는 모든 문서를 보여줌
git init | 디렉토리를 로컬 저장소로 설정함
git config --global user.name " " | 유저네임 설정
git config --global user.email " " | 유저이메일 설정
git config --list | 입력된 정보 확인
touch | 로컬 저장소에 문서 생성
git add 문서명(.) | 로컬 저장소에 문서 등록(로컬 저장소에 add가 필요한 모든 문서 등록)
git commit -m " " | 로컬 저장소에 문서 메세지 등록
git commit -am " " | (이전에 등록됐던 문서에 한해)add와 commit을 동시에 수행
git log | commit된 이력 확인
git status | 현재 로컬 저장소의 상태 확인
