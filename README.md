# circle-rancher-deploy
Project in which a container is deployed in Rancher from CircleCI

For start you need the Environment Variables

	RANCHER_VERSION_NUM : You need the number of version of one realese from https://github.com/rancher/rancher-compose/releases/ example "0.12.5"
	RANCHER_URL : Your Rancher Server URL
   	RANCHER_ACCESS_KEY: Generate Rancher Access Key
   	RANCHER_SECRET_KEY: Generate Rancher Secret Key

If you need deploy the proyect in one different  environment you need add the option "-e" on rancher-compose commands
``` 
rancher-compose -p <stack name> --f <docker compose file> -r <rancher compose file> -e <environment name> up -d
```
