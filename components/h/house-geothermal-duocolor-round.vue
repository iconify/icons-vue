<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bv8jz9bfg"/><path class="buxh1381d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-geothermal-duocolor-round" /></template>
<style>
.buxh1381d {
  d: path("M12 15H9.667a3 3 0 0 1-3-3V9.028A3 3 0 0 1 7.69 6.77l2.333-2.041a3 3 0 0 1 3.952 0l2.333 2.041a3 3 0 0 1 1.024 2.258V12a3 3 0 0 1-3 3z");
}

.bv8jz9bfg {
  stroke-opacity: 0.4;
  d: path("M12 15v4m-6 2v-2h12v2m-8-2v2m4-2v2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
