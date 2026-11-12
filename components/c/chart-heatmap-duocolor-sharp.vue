<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v2nbqr93w"/><path class="hdc4j_jfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-heatmap-duocolor-sharp" /></template>
<style>
.hdc4j_jfs {
  d: path("M3 3h18v18H3Zm9 0v18m-9-9h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v2nbqr93w {
  stroke-opacity: 0.4;
  d: path("M6 7a1 1 0 1 0 2 0a1 1 0 0 0-2 0m11 0h.01M16 17a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
