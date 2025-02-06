
## 仮想環境のセットアップ

1. 仮想環境を作成します：

    ```bash
    python3 -m venv venv
    ```

2. 仮想環境をアクティベートします：

    - **Linux/MacOS:**
    
        ```bash
        source venv/bin/activate
        ```
    
    - **Windows:**
    
        ```bash
        venv\Scripts\activate
        ```

3. 必要なパッケージをインストールします：

    ```bash
    pip install -r requirements.txt
    ```

4. アプリケーションを実行します：

    ```bash
    python app.py
    ```