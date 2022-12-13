# mockend

# 1. List your fake users with a GET request
curl https://mockend.com/org/repo/users

# 2. Fake a creation with a POST
# (don't worry changes aren't persisted)
curl https://mockend.com/org/repo/users \
  -X POST \
  -H "Content-Type: application/json" \
  --data '{"name": "alice"}'

# 3. Access your GraphQL endpoint
https://mockend.com/org/repo/graphql

https://docs.mockend.com/ for more