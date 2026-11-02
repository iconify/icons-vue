<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t5bihgohq"/><path class="q9reugbnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cow-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q9reugbnb {
  d: path("M7 6c3-1 7-1 10 0c.5 1 1 2 1 3c1-.5 2.5 0 3 1c-1 1-2 2-3 2c.5 1 1 2.5 1 5s-2 4-7 4s-7-1.5-7-4s.5-4 1-5c-1 0-2-1-3-2c.5-1 2-1.5 3-1c0-1 .5-2 1-3m0 0c-2.5-.5-4-1.5-4-3m14 3c2.5-.5 4-1.5 4-3M5.298 14C8.6 13 15.4 13 18.702 14");
}

.t5bihgohq {
  stroke-opacity: 0.4;
  d: path("M9 10h.01M15 10h.01M10 17h.01M14 17h.01");
}

</style>
