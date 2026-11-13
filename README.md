# fork-sync

배포(Vercel)용 포크 관리 브랜치. `.github/workflows/sync-upstream.yml`이 15분마다 팀 저장소 `dev`를 이 포크 `dev`로 반영한다.
코드는 `dev` 브랜치에 있다. Vercel Production Branch는 `dev`로 둔다.
