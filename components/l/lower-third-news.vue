<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i3rwgabqs"/><path class="zwx5xme6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lower-third-news" /></template>
<style>
.i3rwgabqs {
  d: path("M2.5 3.5h19v14h-19Zm9.5 14v3m-4 0h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zwx5xme6d {
  d: path("M5.5 10.5h10V14h-10Z");
}

</style>
