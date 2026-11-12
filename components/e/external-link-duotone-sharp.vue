<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z3_leh6an"/><path class="w68ugx1bx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:external-link-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.w68ugx1bx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 5H5v14h14v-5M15 4h5v5m0-5l-7 7");
}

.z3_leh6an {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 5v14H5V5Z");
}

</style>
