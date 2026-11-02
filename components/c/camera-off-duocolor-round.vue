<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m7wsiiesq"/><path class="u677j9bfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-off-duocolor-round" /></template>
<style>
.m7wsiiesq {
  stroke-opacity: 0.4;
  d: path("M10 11c-.543.543-1 1.172-1 2a3 3 0 0 0 3 3c.828 0 1.457-.457 2-1M2 3l19 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u677j9bfh {
  d: path("M10 4c.488-.35.535 0 1 0h2c.64 0 1.36.36 2 1l2 2a4 4 0 0 1 4 4v5m-2 4c-.502.227-1.413 0-2 0H7a4 4 0 0 1-4-4v-5c0-1.9 1.224-3.592 3-4");
}

</style>
