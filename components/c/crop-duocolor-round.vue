<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yy4u890oc"/><path class="lcbvy6bhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crop-duocolor-round" /></template>
<style>
.lcbvy6bhk {
  d: path("M6 3v11a4 4 0 0 0 4 4h11M3 6h3m12 12v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yy4u890oc {
  stroke-opacity: 0.4;
  d: path("M10 6h4a4 4 0 0 1 4 4v4");
}

</style>
