## PHP Doctrine Basic Terminal

![PHP Version Support](https://img.shields.io/badge/php-8.1%2B-brightgreen.svg?style=flat-square) ![Composer Version Support](https://img.shields.io/badge/composer-2.2.9%2B-brightgreen.svg?style=flat-square)

It is an example of using a doctrine with php via a terminal command and sqlite, in a student registration with a telephone relationship and courses linked to it.

## Installation

```bash
composer install
```

## How To Use

This this section explains how to use the command line with php execution.

- New student registration

```bash
php bin/student-insert.php '{name}'
```

- New student registration with phones

```bash
php bin/student-insert.php '{name}' '{phone1}' '{phone2}' ...
```

- New course registration

```bash
php bin/course-insert.php
```

- List of registered students information

```bash
php bin/student-list.php
```

- List of registered courses

```bash
php bin/course-list.php
```

- Relationship with student and course

```bash
php bin/student-enroll.php '{studentId}' '{corseId}'
```

- Number of registered students

```bash
php bin/student-count.php
```

- Search student by name

```bash
php bin/student-search.php
```

- Change student name

```bash
php bin/student-rename.php
```

- Delete student

```bash
php bin/student-delete.php
```