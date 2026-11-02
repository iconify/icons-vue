<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ft1pq8bgo"/><path class="qk4j8ablj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:archive-duocolor-round" /></template>
<style>
.ft1pq8bgo {
  stroke-opacity: 0.4;
  d: path("M3 6a2 2 0 0 1 2-2h14a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qk4j8ablj {
  d: path("M5 8v8a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4V8m-9 4h4");
}

</style>
