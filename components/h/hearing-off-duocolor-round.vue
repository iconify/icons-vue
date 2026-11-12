<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="axcf-wb4p"/><path class="cp2s7tbbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hearing-off-duocolor-round" /></template>
<style>
.axcf-wb4p {
  stroke-opacity: 0.4;
  d: path("m2 2l20 20");
}

.cp2s7tbbr {
  d: path("M6 9c0-.88.19-1.717.53-2.47m3-3A6 6 0 0 1 18 9c0 1.03-.177 1.853-.47 2.53m-2.983 3.017C13.212 15.414 12 16.202 12 18a3 3 0 0 1-6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
