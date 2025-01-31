## 環境を構築

### .net sdk(必須)

windows

```bash
winget install Microsoft.DotNet.SDK.9
```

mac/linux

```
https://dotnet.microsoft.com/ja-jp/download/dotnet/9.0
```

### vscode extension: C# Dev Kit(必須)

search and install `C# Dev Kit`

#### 初回だけ

```bash
dotnet new web -o project-name
```

### 実行

監視モードでサーバーを起動

```bash
# install dependencies
dotnet restore

# watch mode
dotnet watch
```

### api doc

サーバーを起動して、以下の URL で api doc ある
`http://localhost:5000/swagger`
