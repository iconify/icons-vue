<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x_qxwdbyi"/><path class="l-lxy3bml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:invoice-ai-sharp" /></template>
<style>
.l-lxy3bml {
  d: path("M15 10.5q.39 2.86 3.25 3.25q-2.86.39-3.25 3.25q-.39-2.86-3.25-3.25q2.86-.39 3.25-3.25Z");
}

.x_qxwdbyi {
  d: path("M5.5 2.75h13.75v18.5l-.64-.4l-1.12-.7l-.64-.4l-.64.39l-1.17.72l-.64.39l-.64-.4l-1.12-.7l-.64-.4l-.64.4l-1.12.7l-.64.4l-.64-.39l-1.17-.72l-.64-.39l-.64.4l-1.12.7l-.64.4V2.75zM8 7h8m-8 3.5h3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
