<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGuPaD8qfT" x1="-66.775" x2="-66.775" y1="-171.703" y2="-171.817" gradientTransform="matrix(240 0 0 -240 16042 -41206)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ws_mz0uat"/><stop offset="1" class="dc2wrdmah"/></linearGradient></defs><rect fill="url(#SVGuPaD8qfT)" class="c9_0vtxip"/><path class="we-ag-ddj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-favicon" /></template>
<style>
.c9_0vtxip {
  width: 28px;
  height: 28px;
  x: 2px;
  y: 2px;
  rx: 1.75px;
  ry: 1.75px;
}

.dc2wrdmah {
  stop-color: var(--svg-color--f51032, #f51032);
}

.we-ag-ddj {
  fill: var(--svg-color--fff, #fff);
  d: path("m16 22.625l-6.489 3.408l1.239-7.218l-5.25-5.111l7.255-1.054L16 6.083l3.245 6.567l7.255 1.054l-5.25 5.111l1.239 7.218z");
}

.ws_mz0uat {
  stop-color: var(--svg-color--ec790f, #ec790f);
}

</style>
