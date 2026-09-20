<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uzcae5u0u"/><circle class="rbrpubvva"/><path class="k2yvp3gzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:droidcam" /></template>
<style>
.k2yvp3gzz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 39.25v2.74m-4.33-5.38l2.63-1.88l1.09 1.34l1.7-.28l.61-1.61l-1.09-1.33");
}

.rbrpubvva {
  cx: 24px;
  cy: 34.39px;
  r: 4.87px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uzcae5u0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.51 27.25V40a1.94 1.94 0 0 0 1.94 2h33.1a2 2 0 0 0 2-2V27.25ZM39 13.72l2.58-2.56a3 3 0 0 0-4.27-4.26l-2.55 2.6a18.39 18.39 0 0 0-21.51 0l-2.57-2.57A3.22 3.22 0 0 0 8.5 6a3 3 0 0 0-2.12 5.15L9 13.71a18.4 18.4 0 0 0-3.47 10.8v2.74h37v-2.74A18.57 18.57 0 0 0 39 13.72m-19.87 7a2.93 2.93 0 1 1-2.93-2.92a2.93 2.93 0 0 1 2.94 2.9Zm12.65 2.92a2.92 2.92 0 1 1 2.92-2.92a2.92 2.92 0 0 1-2.91 2.9Z");
}

</style>
