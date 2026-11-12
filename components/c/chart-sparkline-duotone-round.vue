<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f9-flfbpi"/><path class="l21x__bqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-sparkline-duotone-round" /></template>
<style>
.f9-flfbpi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16.56 2.452a3.829 3.829 0 1 1 2.88 7.096a3.829 3.829 0 0 1-2.88-7.096");
}

.ft5dv1b6b {
  fill: none;
}

.l21x__bqk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 18l4-4l4 3l5-9m0-4a2.828 2.828 0 1 1 4 4a2.828 2.828 0 0 1-4-4");
}

</style>
