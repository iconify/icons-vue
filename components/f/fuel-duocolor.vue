<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="owzc3mqvp"/><path class="aer2cpbbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fuel-duocolor" /></template>
<style>
.aer2cpbbd {
  d: path("M3 5a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm0 4h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.owzc3mqvp {
  stroke-opacity: 0.4;
  d: path("M13 12h2a2 2 0 0 1 2 2v1a2 2 0 1 0 4 0V8c0-.64-.36-1.36-1-2l-2-2");
}

</style>
