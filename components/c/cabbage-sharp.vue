<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kyt6e8bla"/><path class="sy7_du0sl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cabbage-sharp" /></template>
<style>
.kyt6e8bla {
  d: path("M7.6 7.4a5 5 0 0 1 8.8 0c1.5-1 3.5-1.2 4.5-.4l1.059 1.361L20.4 9.4l1.705 1.895L20.5 12.9c.7 1.5.1 3.3-1.4 3.9c-.5 2.6-3.5 4.2-7.1 4.2s-6.6-1.6-7.1-4.2c-1.5-.6-2.1-2.4-1.4-3.9l-1.605-1.605L3.6 9.4L2.041 8.361L3.1 7c1-.8 3-.6 4.5.4Z");
}

.sy7_du0sl {
  d: path("M7.6 7.4C8 12.75 9.5 17.75 12 21m4.4-13.6C16 12.75 14.5 17.75 12 21");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
