# My Library Project

Мой первый проект для изучения Git.
echo "" >> README.md
echo "## Команда проекта" >> README.md
echo "" >> README.md
echo "| Роль | Имя | Права GitHub | Обязанности |" >> README.md
echo "|------|-----|--------------|-------------|" >> README.md
echo "| Team Lead | Иван | Admin | Управление репозиторием, код-ревью |" >> README.md
echo "| Разработчик | Мария | Write | Создание фич, исправление багов |" >> README.md
echo "| Тестировщик | Алексей | Read | Создание issues, тестирование |" >> README.md

git add README.md
git commit -m "docs: добавлена информация о команде"
git push origin main