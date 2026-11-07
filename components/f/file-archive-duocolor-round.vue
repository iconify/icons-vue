<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wb5pupltj"/><path class="kn5rbrb4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-archive-duocolor-round" /></template>
<style>
.kn5rbrb4f {
  d: path("M13 3H9a4 4 0 0 0-4 4v14M19 9v8a4 4 0 0 1-4 4M13 3l6 6m-6-6v4a2 2 0 0 0 2 2h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wb5pupltj {
  stroke-opacity: 0.4;
  d: path("M10 6h.01M8 8h.01M10 10h.01M8 12h.01M10 16a2 2 0 0 1 2 2v2a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-2a2 2 0 0 1 2-2");
}

</style>
