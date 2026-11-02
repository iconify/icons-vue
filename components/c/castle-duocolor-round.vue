<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d53ospbbr"/><path class="r96z0tspi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:castle-duocolor-round" /></template>
<style>
.d53ospbbr {
  stroke-opacity: 0.4;
  d: path("M9 21v-3a3 3 0 0 1 6 0v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r96z0tspi {
  d: path("M12 11h7a2 2 0 0 1 2 2v4a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4v-4a2 2 0 0 1 2-2zm-6 0V3m12 8V3M6 5h12m-8-2v2m4-2v2");
}

</style>
