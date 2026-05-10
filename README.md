# LEE MIN JUNG · PORTFOLIO

## 폴더 구조

```
my-portfolio/
├── index.html          ← 포트폴리오 메인 파일
├── images/             ← 이미지 폴더 (직접 만들기)
│   ├── project1-thumb.jpg
│   ├── project1-01.jpg
│   └── ...
└── README.md
```

## 시작하는 법

### 1. VS Code + Live Server 설치
1. [VS Code](https://code.visualstudio.com/) 설치
2. VS Code 열고 왼쪽 Extensions(확장) 탭에서 **Live Server** 검색 후 설치

### 2. 포트폴리오 열기
1. VS Code에서 **File → Open Folder** → `my-portfolio` 폴더 선택
2. `index.html` 우클릭 → **Open with Live Server**
3. 브라우저에서 `http://localhost:5500` 자동으로 열림

### 3. 이미지 추가하기
1. `images/` 폴더 만들기
2. 프로젝트 이미지를 `images/` 폴더에 넣기
3. 포트폴리오에서 **편집 모드** 켜기 (우하단 버튼)
4. 프로젝트 카드의 ✏️ 편집 클릭
5. 이미지 URL 입력란에 `images/파일명.jpg` 형식으로 입력

### 이미지 경로 예시
```
images/naver-whale-thumb.jpg
images/naver-whale-01.jpg
images/staaack-thumb.jpg
```

## 주의사항
- 반드시 **Live Server**로 열어야 localStorage가 저장됨
- `file://` 로 직접 열면 이미지 경로가 작동하지 않을 수 있음
- 이미지 파일명에 한글, 공백 사용 금지 (영문, 숫자, `-`, `_` 만 사용)
