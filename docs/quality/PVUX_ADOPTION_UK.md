# TRENDORA: прийняття PVUX v1.0

- **Task ID:** `PVUX-TRENDORA-001`.
- **Джерело:** вимога власника щодо одного Production Visual & UX Quality Gate для всіх поточних і майбутніх продуктів, 2026-10-15.
- **Статус:** `POLICY_CANDIDATE / PRODUCT_UI_UNKNOWN / RELEASE_BLOCKED`.
- **Observed repo:** `ziko1/TRENDORA`; поточна зрілість: `PLACEHOLDER`.
- **Факти:** default branch містить README.md, LICENSE та .gitignore, але не підтверджений виконуваний frontend.
- **Read first:** README.md та майбутні окремі project memory/roadmap/backlog/budget.
- **Повний scoped profile:** [trendora.md](https://github.com/ziko1/ai-team-orchestrator/blob/72e0285809609e2aa557f836f011a452b6e01854/standards/pvux/v1.0/projects/trendora.md) (private upstream, авторизація потрібна).

## Майбутні UX acceptance scenarios

Після появи реального UI перевірити найважливіші user flows, навігацію, теми, помилки, mobile+desktop, локалі та регресійні screenshots.

## Release QA tasks (ще NOT RUN)

- [ ] Описати користувачів, ролі, реальні UI/screens, платформи та окремий project budget.
- [ ] Пов'язати застосовні PVUX-001–PVUX-091 з вимірюваними критеріями та виконуваним кодом.
- [ ] Перевірити WCAG 2.2 AA, responsive, semantics, keyboard, ARIA, локалізації, focus, error/offline/loading.
- [ ] Схвалити snapshot baseline; запустити deterministic actual/diff з negative/positive E2E і реальним viewport.
- [ ] Зафіксувати exact source SHA, artifact hash, actual deployed SHA, платформу/пристрій, дату, reviewer, PASS/FAIL/UNKNOWN.
- [ ] Отримати окремий дозвіл на release/merge/deploy, live HTTPS і device acceptance; до цього статус `RELEASE_BLOCKED`.

Жоден документ не доводить наявності готового застосунку або production QA. Не дублювати канонічні правила, не чіпати інші проєкти чи платні сервіси.
