# CAPA-Bot

> A GitHub bot for the CAPA project

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t capa-bot .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> capa-bot
```

## Contributing

If you have suggestions for how CAPA-Bot could be improved, or want to report a bug, open an issue! I'd love all and any contributions.

## License

[ISC](LICENSE) © 2022 Abhinav Sinha <work.abhinavsinha@gmail.com>
