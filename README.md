# Demo

1. Install .NET 6 SDK.
2. Install docfx v3 using:

    ```bash
    dotnet tool update -g docfx --version "3.0.0-*" --add-source https://docfx.pkgs.visualstudio.com/docfx/_packaging/docs-public-packages/nuget/v3/index.json
    ```

2. Run `docfx build` from this directory to build the site. The `_site` folder contains an xcopy deployable static site.

3. Run `docfx serve` and browse to `http://127.0.0.1:8080/test` to preview the site.

## Known Limitations

- TOC links are not working.
- The `template` is using a slightly modified fork.
- The `template`, `templateBasePath`, `basePath` config is required for now.