<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jvayet_ht"/><path class="mp-l3bbdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-duocolor-round" /></template>
<style>
.jvayet_ht {
  stroke-opacity: 0.4;
  d: path("M16 3v2M2 2l20 20");
}

.mp-l3bbdv {
  d: path("M19 19c-.723 1.037-1.64 2-3 2H8a4 4 0 0 1-4-4V9c0-1.36.963-2.277 2-3m5-1h5a4 4 0 0 1 4 4v5M4 9h5m6 0h5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
