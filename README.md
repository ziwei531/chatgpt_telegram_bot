# ChatGPT Telegram Bot: **Fast. No daily limits. Special chat modes**

This repo is forked from https://github.com/karfly/chatgpt_telegram_bot
## Bot commands
- `/retry` – Regenerate last bot answer
- `/new` – Start new dialog
- `/mode` – Select chat mode
- `/balance` – Show balance
- `/help` – Show help

## Setup
1. Get your [OpenAI API](https://openai.com/api/) key

2. Get your Telegram bot token from [@BotFather](https://t.me/BotFather)

3. Edit `config/config.example.yml` to set your tokens and run 2 commands below (*if you're advanced user, you can also edit* `config/config.example.env`):
    ```bash
    mv config/config.example.yml config/config.yml
    mv config/config.example.env config/config.env
    ```

if Windows:
    ```bash
    move config/config.example.yml config/config.yml
    move config/config.example.env config/config.env
    ```

4. Ensure you have docker installed. Then Run:
    ```bash
    docker-compose --env-file config/config.env up --build
    ```


