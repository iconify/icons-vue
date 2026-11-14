<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="i9uaiogbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:led-matrix" /></template>
<style>
.i9uaiogbw {
  d: path("M6.75 6.75h1.5v1.5h-1.5Zm4.5 0h1.5v1.5h-1.5Zm4.5 0h1.5v1.5h-1.5Zm-9 4.5h1.5v1.5h-1.5Zm4.5 0h1.5v1.5h-1.5Zm4.5 0h1.5v1.5h-1.5Zm-9 4.5h1.5v1.5h-1.5Zm4.5 0h1.5v1.5h-1.5Zm4.5 0h1.5v1.5h-1.5Z");
}

.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
