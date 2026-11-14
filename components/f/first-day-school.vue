<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="id-8-hb8q"/><path class="jxyddgrou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:first-day-school" /></template>
<style>
.id-8-hb8q {
  d: path("M6.5 5.5h11A1.5 1.5 0 0 1 19 7v13a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 20V7a1.5 1.5 0 0 1 1.5-1.5Zm3.5 0v-1a2 2 0 0 1 4 0v1");
}

.jxyddgrou {
  d: path("M8 21.5V16a1.5 1.5 0 0 1 1.5-1.5h5A1.5 1.5 0 0 1 16 16v5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
