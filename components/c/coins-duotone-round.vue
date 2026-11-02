<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qmx8ahsjp"/><path class="rjggz6acn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coins-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qmx8ahsjp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3.472 6.664a6.001 6.001 0 1 1 11.055 4.674A6.001 6.001 0 0 1 3.472 6.664");
}

.rjggz6acn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 9a5 5 0 1 0 10 0A5 5 0 0 0 4 9m14 2a5 5 0 1 1-7 7");
}

</style>
