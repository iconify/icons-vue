<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dr3tx_s2o"/><circle class="e-6ytzbao"/><path class="wz_fvkl4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dust-mask-sharp" /></template>
<style>
.dr3tx_s2o {
  d: path("M4 11c2-2.5 5-3.5 8-3.5s6 1 8 3.5c-.5 4.5-4 8.5-8 9.5c-4-1-7.5-5-8-9.5Zm8-3.5v4");
}

.e-6ytzbao {
  cx: 12px;
  cy: 15px;
  r: 1.75px;
}

.wz_fvkl4s {
  d: path("M4 11L2.788 6.962L5.75 4M20 11l1.212-4.038L18.25 4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
