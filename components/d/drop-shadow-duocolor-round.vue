<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zv47j2bxe"/><path class="vpe2ajr8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drop-shadow-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vpe2ajr8p {
  d: path("M3 7a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Z");
}

.zv47j2bxe {
  stroke-opacity: 0.4;
  d: path("M7 21h10a4 4 0 0 0 4-4V7");
}

</style>
