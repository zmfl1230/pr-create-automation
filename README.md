# 풀리케 자동 생성

**풀리케 자동화 Action입니다. 다음과 같은 조건하에 실행됩니다 :)**
#### ✔️ 생성한 브랜치 명(prefix)

```
branch prefix: hotfix/**
base branch: main
```

```
branch prefix: feature/**
base branch: develop
```

```
branch prefix: bugfix/**
base branch: develop
```

```
branch prefix: refactor/**
base branch: develop
```
<br/>

#### ✔️ 커밋 메세지(postfix - `pr`)

아래 커밋 메세지 내용과 같이 커밋 메세지 뒤에 `pr` 를 붙입니다.  
원격 저장소로 푸시한 모든 브랜치와 커밋내용에 대해 풀리케를 생성하는 것은 비효율적일 수 있으므로,  
`postfix`로 풀리케를 생성할 조건을 추가합니다.

```
feat: initialize project pr
```
