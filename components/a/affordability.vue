<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e8vdn8hxh"/><path class="g2vxby7tq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:affordability" /></template>
<style>
.e8vdn8hxh {
  d: path("M3.5 10.5L12 3.25l8.5 7.25v10h-17ZM12 9v8");
}

.g2vxby7tq {
  d: path("m9 14l3 3l3-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
