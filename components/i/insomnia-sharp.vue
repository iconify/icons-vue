<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u9ua4bczn"/><path class="qywzcubyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:insomnia-sharp" /></template>
<style>
.qywzcubyo {
  d: path("M10.25 14.75a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 1 1 0-3.5Zm6.4-11.95a3.75 3.75 0 1 0 4.19 4.78a3.25 3.25 0 0 1-4.19-4.78Z");
}

.u9ua4bczn {
  d: path("M2.75 16.5c2-3 4.6-4.5 7.5-4.5s5.5 1.5 7.5 4.5c-2 3-4.6 4.5-7.5 4.5s-5.5-1.5-7.5-4.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
