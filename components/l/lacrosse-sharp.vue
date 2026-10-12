<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="em48pvb6f"/><circle class="m-6tq_x6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lacrosse-sharp" /></template>
<style>
.em48pvb6f {
  d: path("m12.2 11.2l-1.8-4.6l-.874-2.271L11.3 3.2c1.3-.7 2.9-.3 4.4.5l4.1 2.4l2.195 1.28L20.8 9.6l-.893 1.637L17.4 10.7l-4.6 1.1Zm.8-5.95l5.25 3m-5.5.25l2.75-3.25m-3 6.25l-9.25 9.25");
}

.m-6tq_x6h {
  cx: 17.5px;
  cy: 17.5px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
