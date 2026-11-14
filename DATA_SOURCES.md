# 선수 데이터 출처

실제 선수 이름, 구단 소속, 포지션, 나이, 국적, 주발, 이적시장 가치와 계약 만료일은 아래 데이터셋에서 가져왔습니다.

- 데이터셋: [dcaribou/transfermarkt-datasets](https://github.com/dcaribou/transfermarkt-datasets)
- 데이터 파일: `players.csv.gz`, `clubs.csv.gz`
- 데이터셋 라이선스: CC0 1.0 (저장소의 [LICENSE](https://github.com/dcaribou/transfermarkt-datasets/blob/master/LICENSE))
- 원 데이터 수집처: Transfermarkt
- 스냅샷 기준일: 2026-07-06
- 게임 적용 시즌: 2025/26
- 이 게임에 포함된 범위: 잉글랜드 프리미어리그, 스페인 라리가, 독일 분데스리가, 이탈리아 세리에 A, 프랑스 리그 1의 선수 3,627명

게임의 1–20 능력치와 잠재력은 원 데이터에 포함되지 않아 시장가치와 포지션을 바탕으로 게임이 추정합니다. 선수단 구분도 원본 데이터가 제공하는 분류가 아니므로, 가져온 선수는 기본적으로 1군에 등록합니다. 선수 소속과 계약 정보는 데이터 스냅샷 이후 변경됐을 수 있습니다.

이 데이터셋에는 요청하신 5개국 하부리그 전체 선수단이 포함되어 있지 않습니다. 현재 포함된 실제 명단은 각국 1부 리그 범위입니다.
