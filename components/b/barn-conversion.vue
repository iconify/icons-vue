<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jc1d8exii"/><path class="xppoz2b0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:barn-conversion" /></template>
<style>
.jc1d8exii {
  d: path("M3 21.5V11l3-5.5l6-3l6 3l3 5.5v10.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xppoz2b0x {
  d: path("M8.5 9.5h7v12h-7Zm3.5 0v12m-3.5-6h7");
}

</style>
