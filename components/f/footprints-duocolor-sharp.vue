<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wtywmkded"/><path class="tiihizmdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:footprints-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tiihizmdq {
  d: path("M3 17V9c0-3 1-4 3-4c3 0 4 2 4 4c0 3-2 4-2 7v5H3zm18-2V7c0-3-1-4-3-4c-3 0-4 2-4 4c0 3 2 4 2 7v5h5z");
}

.wtywmkded {
  stroke-opacity: 0.4;
  d: path("M3 17h5m13-2h-5");
}

</style>
