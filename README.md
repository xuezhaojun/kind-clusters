# kinds-action
The gitHub action that creates multiple kinds of clusters.

## Example:

```yaml
      - name: Setup kind cluster
        uses: xuezhaojun/kind-clusters@main
        with:
          clusters: "hub1,hub2,spoke"
          images: >
            quay.io/open-cluster-management/registration-operator:e2e,
            quay.io/open-cluster-management/registration:e2e,
            quay.io/open-cluster-management/work:e2e,
            quay.io/open-cluster-management/placement:e2e,
            quay.io/open-cluster-management/addon-manager:e2e
```
