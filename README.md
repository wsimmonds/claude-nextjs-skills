# Claude Next.js Skills

Claude Next.js Skills is a POC bundle of automations aimed at seeing if creating skills quickly could improve the Next.js eval scores published by Vercel at https://nextjs.org/evals.

**Baseline (before skills)**

| Model | Success Rate |
| --- | --- |
| Claude Haiku 4.5 | 32% |
| Claude Sonnet 4.5 | 32% |

**Skilled Runs (after skills)**

| Model | Success Rate | Expected Leaderboard Slot |
| --- | --- | --- |
| Claude Haiku 4.5 "Skilled" | 78% (39/50) | 1 |
| Claude Sonnet 4.5 "Skilled" | 76% (38/50) | 2 |

## Result Snapshot

### Claude Haiku 4.5:

📊 Results:
════════════════════════════════════════════════════════════════════════════════
| Eval                                       | Claude Code              |
|--------------------------------------------|--------------------------|
| 000-app-router-migration-simple            | ✅✅✅ (204.8s)          |
| 001-server-component                       | ✅✅✅ (94.4s)           |
| 002-client-component                       | ✅✅✅ (94.7s)           |
| 003-cookies                                | ✅✅✅ (136.7s)          |
| 004-search-params                          | ✅✅✅ (219.1s)          |
| 005-react-use-api                          | ✅✅✅ (138.0s)          |
| 006-server-metadata                        | ✅✅✅ (91.4s)           |
| 007-client-metadata                        | ✅✅❌ (86.0s)           |
| 008-generate-static-params                 | ❌✅❌ (83.0s)           |
| 009-og-images                              | ✅✅✅ (108.0s)          |
| 010-route-handlers                         | ✅✅✅ (69.1s)           |
| 011-client-server-form                     | ✅✅✅ (167.9s)          |
| 012-parallel-routes                        | ✅✅✅ (157.7s)          |
| 013-pathname-server                        | ❌❌❌ (70.8s)           |
| 014-server-routing                         | ✅✅❌ (94.0s)           |
| 015-server-actions-exports                 | ✅✅❌ (69.6s)           |
| 016-client-cookies                         | ❌✅❌ (65.9s)           |
| 017-use-search-params                      | ✅✅❌ (59.7s)           |
| 018-use-router                             | ✅✅✅ (72.6s)           |
| 019-use-action-state                       | ✅✅✅ (120.3s)          |
| 020-no-use-effect                          | ✅✅❌ (92.0s)           |
| 021-avoid-fetch-in-effect                  | ✅✅✅ (238.6s)          |
| 022-prefer-server-actions                  | ✅✅✅ (312.2s)          |
| 023-avoid-getserversideprops               | ✅✅✅ (166.2s)          |
| 024-avoid-redundant-usestate               | ✅✅✅ (111.5s)          |
| 025-prefer-next-link                       | ✅✅✅ (120.9s)          |
| 026-no-serial-await                        | ❌✅✅ (153.3s)          |
| 027-prefer-next-image                      | ✅✅✅ (98.7s)           |
| 028-prefer-next-font                       | ✅✅✅ (90.5s)           |
| 029-use-cache-directive                    | ✅✅✅ (212.0s)          |
| 030-app-router-migration-hard              | ✅✅✅ (453.7s)          |
| 031-ai-sdk-migration-simple                | ✅✅✅ (178.7s)          |
| 032-ai-sdk-model-specification-string      | ✅✅✅ (194.9s)          |
| 033-ai-sdk-v4-model-specification-function | ✅✅✅ (166.7s)          |
| 034-ai-sdk-render-visual-info              | ❌❌❌ (659.4s)          |
| 035-ai-sdk-call-tools                      | ✅✅✅ (338.5s)          |
| 036-ai-sdk-call-tools-multiple-steps       | ✅✅✅ (307.9s)          |
| 037-ai-sdk-embed-text                      | ✅✅✅ (155.0s)          |
| 038-ai-sdk-mcp                             | ✅✅✅ (260.5s)          |
| 039-parallel-routes                        | ✅✅✅ (217.6s)          |
| 040-intercepting-routes                    | ✅✅✅ (208.4s)          |
| 041-route-groups                           | ✅✅✅ (139.1s)          |
| 042-loading-ui                             | ✅✅✅ (123.9s)          |
| 043-error-boundaries                       | ✅✅✅ (138.4s)          |
| 044-metadata-api                           | ✅✅✅ (115.6s)          |
| 045-server-actions-form                    | ✅✅❌ (88.8s)           |
| 046-streaming                              | ✅✅✅ (129.9s)          |
| 047-middleware                             | ✅✅✅ (78.2s)           |
| 048-draft-mode                             | ✅✅✅ (207.6s)          |
| 049-revalidation                           | ✅✅✅ (124.2s)          |
|--------------------------------------------|--------------------------|
| Overall (B/L/T)                            | 45/48/40 (90%, 96%, 80%) |


### Claude Sonnet 4.5:

📊 Results:
════════════════════════════════════════════════════════════════════════════════
| Eval                                       | Claude Code              |
|--------------------------------------------|--------------------------|
| 000-app-router-migration-simple            | ✅✅✅ (164.1s)          |
| 001-server-component                       | ✅✅✅ (88.8s)           |
| 002-client-component                       | ✅✅✅ (109.4s)          |
| 003-cookies                                | ✅✅✅ (138.6s)          |
| 004-search-params                          | ✅✅✅ (223.4s)          |
| 005-react-use-api                          | ✅✅✅ (132.7s)          |
| 006-server-metadata                        | ✅✅✅ (90.8s)           |
| 007-client-metadata                        | ✅✅❌ (81.1s)           |
| 008-generate-static-params                 | ❌✅❌ (78.0s)           |
| 009-og-images                              | ✅✅✅ (105.3s)          |
| 010-route-handlers                         | ✅✅✅ (75.1s)           |
| 011-client-server-form                     | ✅✅✅ (179.3s)          |
| 012-parallel-routes                        | ✅✅✅ (153.3s)          |
| 013-pathname-server                        | ❌❌❌ (78.2s)           |
| 014-server-routing                         | ❌✅❌ (103.1s)          |
| 015-server-actions-exports                 | ✅✅❌ (76.0s)           |
| 016-client-cookies                         | ❌✅❌ (71.5s)           |
| 017-use-search-params                      | ✅✅❌ (64.1s)           |
| 018-use-router                             | ✅✅✅ (77.2s)           |
| 019-use-action-state                       | ✅✅✅ (123.8s)          |
| 020-no-use-effect                          | ✅✅❌ (94.5s)           |
| 021-avoid-fetch-in-effect                  | ✅✅✅ (269.8s)          |
| 022-prefer-server-actions                  | ✅✅✅ (242.4s)          |
| 023-avoid-getserversideprops               | ✅✅✅ (207.7s)          |
| 024-avoid-redundant-usestate               | ✅✅✅ (126.4s)          |
| 025-prefer-next-link                       | ✅✅✅ (96.4s)           |
| 026-no-serial-await                        | ✅✅✅ (220.4s)          |
| 027-prefer-next-image                      | ✅✅✅ (103.4s)          |
| 028-prefer-next-font                       | ✅✅✅ (81.4s)           |
| 029-use-cache-directive                    | ✅✅✅ (208.8s)          |
| 030-app-router-migration-hard              | ✅✅✅ (397.9s)          |
| 031-ai-sdk-migration-simple                | ✅✅✅ (233.2s)          |
| 032-ai-sdk-model-specification-string      | ✅✅✅ (150.4s)          |
| 033-ai-sdk-v4-model-specification-function | ✅✅✅ (118.6s)          |
| 034-ai-sdk-render-visual-info              | ✅✅❌ (567.8s)          |
| 035-ai-sdk-call-tools                      | ✅✅✅ (209.6s)          |
| 036-ai-sdk-call-tools-multiple-steps       | ✅✅✅ (247.7s)          |
| 037-ai-sdk-embed-text                      | ✅✅✅ (181.0s)          |
| 038-ai-sdk-mcp                             | ❌❌❌                   |
| 039-parallel-routes                        | ✅✅✅ (162.7s)          |
| 040-intercepting-routes                    | ✅✅✅ (201.2s)          |
| 041-route-groups                           | ✅✅✅ (147.7s)          |
| 042-loading-ui                             | ✅✅✅ (141.3s)          |
| 043-error-boundaries                       | ✅✅✅ (228.7s)          |
| 044-metadata-api                           | ✅✅✅ (110.0s)          |
| 045-server-actions-form                    | ✅✅❌ (101.0s)          |
| 046-streaming                              | ✅✅✅ (126.4s)          |
| 047-middleware                             | ✅✅✅ (91.2s)           |
| 048-draft-mode                             | ✅✅✅ (210.0s)          |
| 049-revalidation                           | ❌✅✅ (195.9s)          |
|--------------------------------------------|--------------------------|
| Overall (B/L/T)                            | 44/48/39 (88%, 96%, 78%) |

## Outcomes
Does this translate into improved real world code or is Claude now just optimised to better pass evals? This would be a great area to explore.

Please try and let me know.