<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x_dkqe-nn"/><path class="mhcy2mq4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-office-duocolor" /></template>
<style>
.mhcy2mq4h {
  d: path("M4 21V7a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v14M3 21h18M8 9v4m4-4v4m4-4v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x_dkqe-nn {
  stroke-opacity: 0.4;
  d: path("M10 21v-2a2 2 0 1 1 4 0v2");
}

</style>
