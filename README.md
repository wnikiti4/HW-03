# HW-03
Проект devOps тренировка
GitLab Flow:

Основные ветки:
main (или master): основная ветка, содержащая стабильные релизы.
production: ветка для кода, готового к деплою в продакшн.
pre-production (или staging): ветка для кода, готового к тестированию перед деплоем.
Процесс:
Разработка ведется в отдельных ветках, которые сливаются в main.
Когда код готов к тестированию, он сливается в pre-production.
После успешного тестирования код сливается в production. 
