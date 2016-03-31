# deploy gitlab to kubernetes
#COMMOND
kubectl create -f local-volumes.yaml

kubectl create -f postgresql.yaml

kubectl create -f redis.yaml

kubectl create -f gitlab.yaml

#Change all yaml clusterIP and env setting to your virtual ip 
