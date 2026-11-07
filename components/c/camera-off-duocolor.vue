<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iv4xs0jzj"/><path class="fp7iqy6es"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-off-duocolor" /></template>
<style>
.fp7iqy6es {
  d: path("M9.54 4.54c.488-.35.995-.54 1.46-.54h2c.64 0 1.36.36 2 1l2 2h2a2 2 0 0 1 2 2v7m-2 4H5a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2h1");
}

.iv4xs0jzj {
  stroke-opacity: 0.4;
  d: path("M9.879 10.879a3 3 0 0 0 4.243 4.243M2 3l19 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
