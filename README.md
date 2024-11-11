# Использование гибридного хранилища в Yandex Managed Service for ClickHouse

С помощью гибридного хранилища вы можете хранить часто используемые данные на сетевых дисках кластера [Managed Service for ClickHouse®](https://yandex.cloud/ru/docs/managed-clickhouse), а редко используемые данные — в [Yandex Object Storage](https://yandex.cloud/ru/docs/storage). Автоматическое перемещение данных между этими уровнями хранения поддерживается только для таблиц семейства [MergeTree](https://clickhouse.com/docs/ru/engines/table-engines/mergetree-family/mergetree).

Подготовка инфраструктуры для Managed Service for ClickHouse® через Terraform описана в [практическом руководстве](https://yandex.cloud/ru/docs/tutorials/dataplatform/clickhouse-hybrid-storage), необходимый для настройки конфигурационный файл [clickhouse-hybrid-storage.tf](clickhouse-hybrid-storage.tf) расположен в этом репозитории.
