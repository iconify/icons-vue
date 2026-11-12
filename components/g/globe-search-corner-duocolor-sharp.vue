<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fzwh2xuoy"/><path class="fdebf5bgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:globe-search-corner-duocolor-sharp" /></template>
<style>
.fdebf5bgb {
  d: path("M17 10a7 7 0 1 0-7 7m0-14c-4 0-4 14 0 14m0-14c2 0 3 3.5 3 7M3 10h14");
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
