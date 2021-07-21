### Difference between ReplicaSet and ReplicationController

- Replication Controller (RC) is the original form of replication in Kubenetes.
- Replica Sets (RS) is the new one replacing.
- RC and RS are very similar except the `selector` part.
- RS uses `matchLabels` instead of `label`.
- The main difference between a RC and a RS is that the `rolling-update` command works with RC but not with RS.
- RS are meant as the backend for the Deployments.


[reference](https://www.mirantis.com/blog/kubernetes-replication-controller-replica-set-and-deployments-understanding-replication-options/)
