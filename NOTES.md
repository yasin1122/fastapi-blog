1288 curl -LsSf https://astral.sh/uv/install.sh | sh\n
1289 uv init fastapi_blog
1291 uv add "fastapi[standard]"
1293 uv sync
1294 uv run fastapi dev main.py
