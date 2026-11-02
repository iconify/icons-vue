<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tsi_y2btm"/><path class="w7mc2oblu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:inbox-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tsi_y2btm {
  stroke-opacity: 0.4;
  d: path("M3 13h4l3 3h4l3-3h4");
}

.w7mc2oblu {
  d: path("M3 4h18v16H3Z");
}

</style>
