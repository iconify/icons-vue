<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="noeq1abwj"/><path class="n736056kd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:devices-duocolor-round" /></template>
<style>
.n736056kd {
  d: path("M15 13a3 3 0 0 1 6 0v4a3 3 0 0 1-6 0Z");
}

.noeq1abwj {
  stroke-opacity: 0.4;
  d: path("M17 6a2 2 0 0 0-2-2H7a4 4 0 0 0-4 4v4a4 4 0 0 0 4 4h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
