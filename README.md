# Linux

### WSL2로 Linux사용하기

### Microsoft Store에서 Windows Terminal 설치
관리자 권한으로 실행 후
<br/> > dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
<br/> > dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
<br/> 두 개의 명령어를 차례대로 실행

### Ubuntu 설치 후 사용자이름 및 패스워드 지정
<br/> > wsl -l 명령어 실행
<br/> > wsl -l -v   //    버전확인
<br/> > wsl --set--version Ubuntu 2   //    버전2로 바꿈
<br/> > wsl --set-default-version 2   //    새로 설치되는 모든 배포판에 WSL2 기본값으로 설정

WSL2로 Ubuntu 새로운 탭 열어서 사용하기
