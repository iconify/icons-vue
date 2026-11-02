<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d8b23fbyc"/><path class="diru-nb9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-left-duocolor-round" /></template>
<style>
.d8b23fbyc {
  stroke-opacity: 0.4;
  d: path("M4 3v18");
}

.diru-nb9a {
  d: path("M8 7a3 3 0 0 1 3-3h6a3 3 0 0 1 0 6h-6a3 3 0 0 1-3-3m0 10a3 3 0 0 1 3-3h2a3 3 0 0 1 0 6h-2a3 3 0 0 1-3-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
