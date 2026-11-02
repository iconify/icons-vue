<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yuqmkqnrx"/><path class="ubrpbbcap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cable-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ubrpbbcap {
  d: path("M3 7a2 2 0 0 1 2-2h4a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2m10 10a2 2 0 0 1 2-2h4a2 2 0 1 1 0 4h-4a2 2 0 0 1-2-2M5 3v2m4-2v2m6 14v2m4-2v2");
}

.yuqmkqnrx {
  stroke-opacity: 0.4;
  d: path("M7 9a3 3 0 0 0 3 3h4a3 3 0 0 1 3 3");
}

</style>
