# Lightweight 한 개발환경 설정 2 #

## 환경변수 추가 ##

* binary 폴더까지 환경변수에 추가.

* vscode를 intel parallel studio xe 환경에서 열기위한 설정
```dos
call "C:\Program Files (x86)\IntelSWTools\compilers_and_libraries\windows\bin\ipsxe-comp-vars.bat" intel64 vs2019
start "Visual Studio Code with Intel Compiler" /B "C:\Program Files\Microsoft VS Code\Code.exe"
```
* [Visual Studio Code setup for C++](https://goodgodgd.github.io/ian-flow/archivers/vscode-tutorial)
