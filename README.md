# TODO List API
This API created for practice.

## Usage
<details>
  <summary>Using Docker</summary>
  Run <code>docker compose up -d</code>
</details>
<details>
  <summary>Without Using Docker</summary>
  <ol>
    <li>Run <code>make build</code> to build the source code.</li>
    <li>Run <code>make install</code> to move compiled binary to <code>/usr/local/bin</code> directory.</li>
    <li>Execute binary <code>/usr/local/bin/todo-app-api</code>.</li>
  </ol>
</details>

## TODO List
- [x] Implement API Versioning
- [x] Database Connection
- [x] Add Dockerfile
- [x] Add docker-compose.yaml
- [ ] Support configuration using .yaml files
- [ ] Add Support for User Specific Todo Lists
- [ ] Implement Authentication
- [ ] Implement Request Validation
- [ ] Implement Caching using Redis
- [x] Implement Rate Limiting

## License
The [MIT](https://github.com/yunusemre12500/todo-list-api/blob/main/LICENSE) License
