<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dikiu0sii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bat-hanging" /></template>
<style>
.dikiu0sii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3h17m-10 0v3m3-3v3M8 6h8q.25 2.5 1.25 4q-1.5 1.5-1 3.5Q15 15.5 14 16h-4q-1-.5-2.25-2.5q.5-2-1-3.5q1-1.5 1.25-4Zm2 10l-.5 4.5l1.5-1.25h2l1.5 1.25L14 16");
}

</style>
