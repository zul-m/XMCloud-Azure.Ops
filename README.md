# XM Cloud Starter Kit (Next JS) With Azure DevOps deployment pipelines

## QUICK START

1. In an ADMIN terminal:

    ```ps1
    .\init.ps1 -InitEnv -LicenseXmlPath "C:\path\to\license.xml" -AdminPassword "DesiredAdminPassword"
    ```

2. Restart your terminal and run:

    ```ps1
    .\up.ps1
    ```

3. Follow the instructions to [deploy to XM Cloud](#deploy-to-xmcloud)

4. Create Edge token and [query from edge](#query-edge)

*** 

## About this Solution
This solution is designed to help developers learn and get started quickly
with XMCLoud + SXA while using Auzre DevOps. The solution contains three pipelines at the root level..
1. build-dotnet.yml - Used to build the code on every commit or PR. We can configure it as per requirement.
2. deploy-xmc.yml - Used to deploy XMC using the latest code.
3. deploy.yml - Used to deploy to Vercel.


