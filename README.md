Simple flask web app with fully automated CI/CD pipeline using github actions and AWS
On pushing to main, it automatically runs tests with pytest, builds a docker container and deploys it on AWS cloud.

### Local setup:
```bash
docker build -t devops-app .
docker run -d -p 5000:5000 devops-app
