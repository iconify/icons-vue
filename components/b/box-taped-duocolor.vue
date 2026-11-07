<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g1dr-uv8b"/><path class="gq6z8sbdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-taped-duocolor" /></template>
<style>
.g1dr-uv8b {
  stroke-opacity: 0.4;
  d: path("m7.5 4.222l9 4.445");
}

.gq6z8sbdb {
  d: path("M21 12v4.934a1 1 0 0 1-.557.897l-8 3.95a1 1 0 0 1-.886 0l-8-3.95A1 1 0 0 1 3 16.934V7.066a1 1 0 0 1 .557-.897l8-3.95a1 1 0 0 1 .886 0l8 3.95a1 1 0 0 1 .557.897zM3.16 6.523L12 10.89l8.84-4.366M12 10.89v10.996");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
