<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="di2ctevzd"/><path class="q6-7cxbxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coin-jar-duocolor-round" /></template>
<style>
.di2ctevzd {
  stroke-opacity: 0.4;
  d: path("M6 5a2 2 0 1 0 4 0a2 2 0 0 0-4 0m7 2a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q6-7cxbxw {
  d: path("M8 12v2l-1 1c-.64.64-1 1.72-1 3v1a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2v-1c0-1.28-.36-2.36-1-3l-1-1v-2m-9 0h10");
}

</style>
