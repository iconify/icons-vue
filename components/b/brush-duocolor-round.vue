<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ecy1zkb4e"/><path class="zyi9si3_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brush-duocolor-round" /></template>
<style>
.ecy1zkb4e {
  stroke-opacity: 0.4;
  d: path("M10 3v3m4-3v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zyi9si3_e {
  d: path("M10 19v-5H8a2 2 0 0 1-2-2V7a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v5a2 2 0 0 1-2 2h-2v5a2 2 0 1 1-4 0m-4-9h12");
}

</style>
