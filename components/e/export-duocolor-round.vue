<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iyqeu-beg"/><path class="x9vys6b8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:export-duocolor-round" /></template>
<style>
.iyqeu-beg {
  stroke-opacity: 0.4;
  d: path("m15 6l-3-3l-3 3m3-3v12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x9vys6b8c {
  d: path("M5 7a2 2 0 0 0-2 2v8a4 4 0 0 0 4 4h10a4 4 0 0 0 4-4V9a2 2 0 0 0-2-2");
}

</style>
