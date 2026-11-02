<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h3ynmu6py"/><path class="ydmp8rb4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-right-duocolor-round" /></template>
<style>
.h3ynmu6py {
  stroke-opacity: 0.4;
  d: path("M20 3v18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ydmp8rb4e {
  d: path("M4 7a3 3 0 0 1 3-3h6a3 3 0 0 1 0 6H7a3 3 0 0 1-3-3m4 10a3 3 0 0 1 3-3h2a3 3 0 0 1 0 6h-2a3 3 0 0 1-3-3");
}

</style>
