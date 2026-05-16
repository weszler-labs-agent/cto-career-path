# Production Deployment Plan

## Status
Ready for verification. Secrets added.

## Prerequisites
- [x] GitHub PAT provisioned (`GH_PAT`)
- [x] Cloudflare API Token
- [x] Cloudflare Account ID

## Deployment Steps
1.  Add `CLOUDFLARE_API_TOKEN` and `CLOUDFLARE_ACCOUNT_ID` as GitHub secrets.
2.  Trigger CI/CD pipeline.
3.  Verify successful deployment to Cloudflare Pages.
4.  Configure custom domain (sebastianweszler.com).
5.  Configure Plausible analytics and Resend email integration.
