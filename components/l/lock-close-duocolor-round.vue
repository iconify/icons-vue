<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cr709fn9c"/><path class="qoxgw4bwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-close-duocolor-round" /></template>
<style>
.cr709fn9c {
  stroke-opacity: 0.4;
  d: path("m10 13l4 4m0-4l-4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qoxgw4bwg {
  d: path("M4 13a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm4-4V7a4 4 0 1 1 8 0v2");
}

</style>
