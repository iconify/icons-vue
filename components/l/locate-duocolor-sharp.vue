<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u0grsjsan"/><path class="ccvet5pco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:locate-duocolor-sharp" /></template>
<style>
.ccvet5pco {
  d: path("M5 12a7 7 0 1 0 14 0a7 7 0 0 0-14 0m7-9v2m0 14v2m-9-9h2m14 0h2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u0grsjsan {
  stroke-opacity: 0.4;
  d: path("M9 12a3 3 0 0 1 6 0m0 0a3 3 0 0 1-6 0");
}

</style>
