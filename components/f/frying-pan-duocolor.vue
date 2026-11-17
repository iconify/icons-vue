<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rqyts8bos"/><path class="qgbasobcj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:frying-pan-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qgbasobcj {
  d: path("M3 11h12v3a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z");
}

.rqyts8bos {
  stroke-opacity: 0.4;
  d: path("m15 11l6-3");
}

</style>
