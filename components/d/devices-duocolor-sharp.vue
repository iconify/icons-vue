<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e0f4dvbbo"/><path class="v0e0kyiwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:devices-duocolor-sharp" /></template>
<style>
.e0f4dvbbo {
  stroke-opacity: 0.4;
  d: path("M17 6V4H3v12h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v0e0kyiwn {
  d: path("M15 10h6v10h-6Z");
}

</style>
