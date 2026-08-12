# B1-3
         워크플로우
# 🚀 [과제] 자동화 도구 비교 및 자유 주제 구현 프로젝트

## 🎯 1. 과제 목표

* **Trigger와 Action의 개념:** 
  Trigger는 자동화를 시작시키는 조건(예: 구글 시트에 새 행 추가)이고,
  Action은 Trigger 발생 시 실행되는 작업(예: Discord에 메시지 전송)이다.

* **조건 분기(Filter/Router)의 역할:** 
  [아직 미구현 - 프로젝트2에서 추가 예정]

* **도구 비교 및 선택 이유:** 
  [도구 B 구현 후 작성 예정]

* **자동화 흐름 설명:** 
  구글 폼 제출 → 구글 시트 저장 → Make 감지 → 
  HTTP 요청 → Discord 메시지 전송

---

## ✅ 2. 체크리스트
- [x] 실제 동작하는 워크플로우인가?
- [ ] Trigger 1개 이상, Action 2개 이상 포함?  ← ⚠️ 확인 필요
- [ ] 조건 분기 1개 이상?  ← ⚠️ 미구현
- [ ] 분기 경로 각각 실행 캡처?  ← ⚠️ 미구현
- [ ] 민감정보 마스킹 처리?
- [x] 무료 플랜으로 구성

---

## 🛠️ 3. [프로젝트 1]

### 3.1. 워크플로우 개요
* **워크플로우 설명:** 
  구글 폼 제출 → 구글 시트 저장 → Discord 알림 전송

### 3.2. 도구 A (Make) 구현 결과
* **사용한 도구:** Make
* **구현 과정 요약:** 
  Google Sheets Watch New Rows(Trigger) → 
  HTTP Make a Request(Discord Webhook 전송)
* **캡처:** [스크린샷 첨부]

  <img width="1052" height="483" alt="image" src="https://github.com/user-attachments/assets/0f2b656a-de1e-4415-839e-ad4927aeb9ce" />
