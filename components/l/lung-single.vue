<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zq7aso-0q"/><path class="s8lgvbkjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lung-single" /></template>
<style>
.s8lgvbkjx {
  fill: currentColor;
  d: path("M10.5 7c-3-.5-7 3.5-7 9c0 2.75 1.5 4.25 3.5 3.75s3.5-1.5 3.5-3.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zq7aso-0q {
  d: path("M10.5 7c-3-.5-7 3.5-7 9c0 2.75 1.5 4.25 3.5 3.75s3.5-1.5 3.5-3.75Zm3 0c3-.5 7 3.5 7 9c0 2.75-1.5 4.25-3.5 3.75s-3.5-1.5-3.5-3.75ZM12 2.5v5M10.5 9L12 7.5L13.5 9");
}

</style>
