<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdyg8mbcn"/><path class="q9pg4yu3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:head-circumference" /></template>
<style>
.q9pg4yu3z {
  d: path("M11.25 3.75C10.75 2.5 12.5 2 12.75 3M3.5 8.25c4.5 2.5 12.5 2.5 17 0m-17.25 3C8 13.5 16 13.5 20.75 11.25M9 15.5h.01m5.99 0h.01M10.5 18q1.5 1.125 3 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdyg8mbcn {
  d: path("M3.25 12.5a8.75 8.75 0 1 0 17.5 0a8.75 8.75 0 1 0-17.5 0Z");
}

</style>
