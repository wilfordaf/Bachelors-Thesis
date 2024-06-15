# Автор: Юрпалов Сергей Николаевич ИСУ 311486

## Предисловие

Добрый день! В качестве темы своей ВКР я выбрал проект “Разработка сервиса умного поиска бизнес-процессов с использованием методов машинного обучения для 1С Центр Управление Предприятием”, который разрабатывал в компании “BIA Technologies” на должности “Инженер по машинному обучению”. К сожалению, полная кодовая база и детали используемых для обучения и тестирования данных находятся под NDA, я не смогу продемонстрировать их в рамках доклада. В этом репозитории располагается текст моей ВКР, содержащий важные сниппеты кода и демонстрационные сфабрикованные примеры данных. Надеюсь, их будет достаточно для оценки моей квалификации.

## Навигация

#### ВКР
* **Глава 1** - Описание предметной области, постановка задачи.
* **Глава 2** (приложения А и Б) - Исследование данных, извлечение пользовательского ввода из шаблонов, проведение аугментации с использованием LLM.
* **Глава 3** (приложение В) - Создание универсального модуля обработки текстовых данных, использованная архитектура и технологии.
* **Глава 4** (приложение Г) - Выбор метрик для оценки моделей, проведение экспериментов, выбор лучшей модели.
* **Глава 5** (приложение Д) - Разработка сервиса с API для осуществления доступа к модели, проработка связи с БД ClickHouse и ClearML.

#### Изображения
* _/assets/uml_ - диаграммы, отражающие всю важную информацию о разрабатываемом проекте, модулях
  <img src="/assets/uml/deployment.png" alt="deployment" width="635" height="549"/>
* _/assets/code_ - все сниппеты кода, которые были согласованы Службой Безопасности для публикации
  <img src="/assets/code/model_research/cnn_architecture.png" alt="cnn" width="539" height="553"/>
