<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f91b9b8aq"/><path class="tfi6fcbzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-download-duocolor-round" /></template>
<style>
.f91b9b8aq {
  stroke-opacity: 0.4;
  d: path("m9 15l3 3l3-3m-3 3v-6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tfi6fcbzc {
  d: path("M13 3H9a4 4 0 0 0-4 4v10a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4V9m-6-6l6 6m-6-6v4a2 2 0 0 0 2 2h4");
}

</style>
