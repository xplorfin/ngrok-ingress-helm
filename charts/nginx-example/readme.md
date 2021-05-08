Nginx example provides an exmple of an nginx chart using ngrok

## Configuration

| Parameter        | Description                   | Default |
|------------------|-------------------------------|---------|
| image.repository | nginx docker image            | nginx   |
| image.tag        | nginx tag                     | latest  |
| ports.container  | nginx container port          | 80      |
| ports.service    | nginx service port            | 80      |
| env              | list of enviornment variables | none    |
| ngrok.enabled    | true                          |         |
