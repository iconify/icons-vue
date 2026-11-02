<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zyqlyotss"/><path class="mjabu8b4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-line-duocolor-round" /></template>
<style>
.mjabu8b4j {
  d: path("m3 16l3-3a2.83 2.83 0 0 1 4 0a2.83 2.83 0 0 0 4 0l7-7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zyqlyotss {
  stroke-opacity: 0.4;
  d: path("M3 4v12a4 4 0 0 0 4 4h14");
}

</style>
