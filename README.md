# Lyceum

## Установка и запуск

### Установить python с официального сайта (версии из перечисленных: 3.8, 3.9, 3.10, 3.11, 3.12) и Git, если они у вас не были установлены

### Откройте консоль

### Склонируйте репозиторий

```commandline
git clone https://gitlab.crja72.ru/django/2024/autumn/course/students/184206-id-quartz-course-1187 <путь к папке, в которую вы хотите клонировать>
```

### Перейдите в папку с репозиторием

```comandline
cd <путь до папки>
```

### Создайте виртуальное окружение

#### Linux

```comandline
python3 -m venv venv
```

#### Windows

```commandline
python -m venv venv
```

### Активируйте виртуальное окружение

#### Linux

```commandline
source venv/bin/activate
```

#### Windows

```commandline
venv\Scripts\activate.bat
```

### Установите зависимости из файла requirements.txt

#### Linux

```commandline
pip3 install -r requirements/dev.txt
```

#### Windows

```commandline
pip install -r requirements\dev.txt
```

### Перейдите к расположению файла manage.py

```commandline
cd lyceum
```

### Запустите сервер

#### Linux

```commandline
python3 manage.py runserver
```

#### Windows

```commandline
python manage.py runserver
```

### Откройте в браузере адрес, который выведется в консоль. (127.0.0.1:8000 по умолчанию)

Обратите внимание, что проект использует переменные окружения. Как создать файл .env описано в файле .env.template
