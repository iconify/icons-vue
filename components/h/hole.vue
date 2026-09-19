<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iimPJuj)" class="uemnxtvqp"/><path fill="url(#iVscicM)" class="fzdx34faa"/><defs><radialGradient id="iimPJuj" cx="0" cy="0" r="1" gradientTransform="matrix(4.75001 -11.87503 12.18115 4.87246 23.25 15.613)" gradientUnits="userSpaceOnUse"><stop class="uhuniqbrj"/><stop offset=".989" class="ima_0m4pe"/></radialGradient><radialGradient id="iVscicM" cx="0" cy="0" r="1" gradientTransform="matrix(9.74999 -19.62496 54.14327 26.89922 10.5 31.738)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="fqs2vpbze"/><stop offset="1"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hole" /></template>
<style>
.fqs2vpbze {
  stop-color: var(--svg-color--37275e, #37275E);
}

.ft5dv1b6b {
  fill: none;
}

.fzdx34faa {
  d: path("M16 30.067c7.185 0 13.01-3.157 13.01-7.051s-5.825-7.05-13.01-7.05s-13.01 3.156-13.01 7.05s5.825 7.05 13.01 7.05");
}

.ima_0m4pe {
  stop-color: var(--svg-color--90829f, #90829F);
}

.uemnxtvqp {
  d: path("M16 30.137c7.732 0 14-3.643 14-8.137s-6.268-8.137-14-8.137S2 17.506 2 22s6.268 8.137 14 8.137");
}

.uhuniqbrj {
  stop-color: var(--svg-color--d8d1df, #D8D1DF);
}

</style>
