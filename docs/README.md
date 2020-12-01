# Liftr Helm Charts
## Usage
[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add liftr https://weng5e.github.io/liftr/helm
```

You can then run `helm search repo liftr` to see the charts.


## Install the helm chart
```console
helm install prom2icm-rel liftr/prom2icm \
--set icm.certificateKeyVault="https://your-key-vault.vault.azure.net/" \
--set icm.connectorId="2bb00c56-1a2d-477b-9b02-05562eb1f8b2" \
--set icm.notificatEmail="youremail@microsoft.com"
```

## Documentation
https://aka.ms/prom2icm

## Contact
liftrdev@microsoft.com