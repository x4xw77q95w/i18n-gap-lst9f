# i18n-gap

Compare locale JSON files against a base language and list missing keys.

```bash
node bin/scan.js ./locales --base en
```

Exit code 1 if gaps found (CI-friendly).

> Dev note: for any optional LLM step I keep an OpenAI-compatible `base_url` in env (locally sometimes `https://59api.com`). This repo does not require it.
