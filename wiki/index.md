---
created: 2026-11-13
updated: 2026-11-13
---
# 세법 자료 위키

**기존 법령집은 파일명과 달리 2013년 개정 법령이 섞여 있습니다. 새 2026 집행기준·신고안내와 출처·적용 시점을 구분합니다. 어느 자료도 개별 사안의 현행법 판정을 대신하지 않습니다.**

[사용 안내](../README.md) · [운영 규칙](schema.md) · [작업 이력](log.md) · [검토 사항](review.md)

## 출처

- [원본 목록](sources/index.md): 보관 위치·해시·반영 상태.
- [세법 PDF 분석](sources/tax-law-2011.md): 전체 3,978쪽의 구성, 버전 혼재와 분석 범위.
- [Karpathy의 LLM Wiki](sources/karpathy-llm-wiki.md): 원본·위키·스키마 분리와 이번 적용.

## 추가 집행기준과 신고안내

- [2026 자료 묶음 분석](sources/additions-20261113.md): 추가 PDF 12개, 중복 제외 11개·1,925쪽의 출처·기준일·추출 품질.
- [국세기본법](sources/national-tax-framework-guidance.md) · [국세징수법](sources/national-tax-collection-guidance.md): 공통 원칙·권리와 징수·압류 절차를 구분합니다.
- [부가가치세](sources/vat-guidance.md) · [개별소비세·인지세·주세·주류면허법](sources/excise-stamp-liquor-guidance.md): 공급·문서·주류·면허 관련 기준.
- [종합부동산세·증권거래세](sources/property-securities-guidance.md): 보유와 주권 거래를 나누고 동일 해시 사본은 보존합니다.
- [소득세](sources/income-tax-guidance.md) · [법인세](sources/corporate-tax-guidance.md): 납세자 지위·소득·경비·귀속시기.
- [상속세·증여세](sources/inheritance-gift-guidance.md) · [양도소득세](sources/capital-gains-guidance.md) · [조세특례](sources/tax-incentives-guidance.md): 이전 원인·시점·평가·조건부 감면.
- [2026 원천세 신고안내](sources/withholding-2026.md): 원천징수·신고·납부·지급명세서의 구분과 작성 유의점.

## 법률별 탐색

| 문서 | PDF 페이지 | 읽는 관점 |
| --- | --- | --- |
| [국세기본법](laws/national-tax-framework.md) | 3–223 | 국세 공통 원칙·납세의무·불복 |
| [법인세법](laws/corporate-income-tax.md) | 224–1290 | 법인의 소득과 익금·손금 |
| [소득세법](laws/income-tax.md) | 1291–2384 | 개인의 소득 구분 |
| [부가가치세법](laws/value-added-tax.md) | 2385–2906 | 공급·수입과 매입세액 |
| [상속세 및 증여세법](laws/inheritance-gift-tax.md) | 2907–3410 | 사망·증여에 따른 재산 이전 |
| [지방세기본법](laws/local-tax-framework.md) | 3411–3463 | 지방세 공통 절차·권리 |
| [지방세기본법 시행령](laws/local-tax-enforcement-decree.md) | 3464–3495 | 법률의 위임과 절차 구체화 |
| [지방세기본법 시행규칙](laws/local-tax-enforcement-rule.md) | 3496–3642 | 신청·통지·서식 |
| [지방세법](laws/local-tax.md) | 3643–3978 | 지방세 세목별 과세요건 |

페이지는 PDF 뷰어의 물리적 순번입니다. 표지·목차는 1–2쪽입니다. 3단 비교 구간에는 해당 법률의 시행령·시행규칙이 함께 실려 있습니다.

## 공통 개념

- [세목을 구분하는 읽기 지도](concepts/tax-map.md): 국세·지방세, 공통 절차·개별 세목을 구분합니다.
- [과세요건과 소득·거래·재산](concepts/taxable-events.md): 납세자와 과세대상을 먼저 확인합니다.
- [과세 원칙과 납세자 권리](concepts/principles-and-remedies.md): 실질과세·근거과세·신고 정정과 불복을 연결합니다.
- [자료 유형과 적용 시점](concepts/source-authority-and-versioning.md): 법령·집행기준·신고안내의 역할과 기준월을 구분합니다.
- [원천징수 업무 체크리스트](concepts/withholding-workflow.md): 소득 지급과 신고·납부·명세서 제출을 나누어 확인합니다.

## 확인 수준

기존 법령집 3,978쪽과 추가 고유 자료 1,925쪽을 모두 기계적으로 추출했습니다. 위키는 구조와 선별 핵심 조문·집행기준·신고 절차의 분석입니다. 모든 조문·표·서식을 전수 법률 검토한 결과가 아닙니다. 자료별 공백 추출·문자 매핑과 화면 확인 범위는 각 출처 문서에 표시했습니다.
