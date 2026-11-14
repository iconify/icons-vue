<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="un_78vbmo"/><path class="na0ceibki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deli-scale" /></template>
<style>
.na0ceibki {
  d: path("M7 14.25h10v4.5H7Zm2.5 2.25h2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.un_78vbmo {
  d: path("M2.5 5h19C21 7.5 18 8.5 12 8.5S3 7.5 2.5 5ZM12 8.5v3m-8.5 0h17v10h-17Z");
}

</style>
