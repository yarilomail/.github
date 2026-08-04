# Yarilo Mail

**Yarilo** is a modern, cloud-native mail server written in Go — IMAP, POP3, LMTP, Sieve and SMTP proxying in a single, horizontally scalable service designed to run on Kubernetes.

🌐 **Website:** [yarilomail.org](https://yarilomail.org)

## Projects

| Repository | Description |
|---|---|
| [yarilo](https://github.com/YariloMail/yarilo) | The mail server itself — IMAP/POP3/LMTP and SMTP proxy, Sieve filtering, full-text search, quota, replication-ready storage backends (maildir, mdbox, sdbox) |
| [yarilo-loadtest](https://github.com/YariloMail/yarilo-loadtest) | Load generator with IMAP, POP3, LMTP and JMAP drivers, per-command latency stats and a size-configurable mail corpus |
| [mailfrom-milter](https://github.com/YariloMail/mailfrom-milter) | Postfix milter enforcing MAIL FROM / From: header domain alignment for authenticated SMTP sessions |
| [website](https://github.com/YariloMail/website) | yarilomail.org — VitePress static site |

## Highlights

- ⚙️ **Single binary, config-driven** — every deployment shape (all-in-one, proxy + backend, director ring) is a configuration change, never a rebuild
- ☸️ **Kubernetes-first** — Helm chart included, stateless proxies in front of stateful backends
- 📦 **Multiple mailbox formats** — maildir, mdbox and sdbox on shared storage
- 🔍 **Full-text search** — built-in FTS indexing
- 🧹 **Sieve filtering** — server-side mail filtering with ManageSieve support
- 🔐 **Modern auth** — SCRAM, OAuth2/XOAUTH2 and more via SQL, LDAP or static passdbs

## Contact

📮 [support@yarilomail.org](mailto:support@yarilomail.org)
