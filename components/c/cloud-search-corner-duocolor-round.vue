<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fzwh2xuoy"/><path class="cjcrnhgsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-search-corner-duocolor-round" /></template>
<style>
.cjcrnhgsj {
  d: path("M7 19A5 5 0 0 1 7 9c1.819-6.366 9.428-6.115 10.79 0");
}

.fzwh2xuoy {
  stroke-opacity: 0.4;
  d: path("M18 18a2.828 2.828 0 1 1-4-4a2.828 2.828 0 0 1 4 4m0 0l3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
