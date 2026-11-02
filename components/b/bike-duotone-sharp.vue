<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i90b2mbyl"/><path class="p6uz76bvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bike-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i90b2mbyl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M1.393 15.053a5.001 5.001 0 1 1 9.213 3.896a5.001 5.001 0 0 1-9.213-3.896m12 0a5.001 5.001 0 1 1 9.213 3.896a5.001 5.001 0 0 1-9.213-3.896M5 17a1 1 0 1 0 2 0a1 1 0 0 0-2 0m12 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.p6uz76bvs {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 17a4 4 0 1 1 8 0m0 0a4 4 0 1 1-8 0m12 0a4 4 0 1 1 8 0m0 0a4 4 0 1 1-8 0m-8 0L9 5M8 9h8m2 8L15 5M6 5h4m5 0h3a2 2 0 0 1 2 2");
}

</style>
