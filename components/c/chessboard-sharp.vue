<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lpshhqfzv"/><path class="j6-ofzb8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chessboard-sharp" /></template>
<style>
.j6-ofzb8x {
  d: path("M6.75 6.75h1.5v1.5h-1.5zm6 0h1.5v1.5h-1.5zm-3 3h1.5v1.5h-1.5zm6 0h1.5v1.5h-1.5zm-9 3h1.5v1.5h-1.5zm6 0h1.5v1.5h-1.5zm-3 3h1.5v1.5h-1.5zm6 0h1.5v1.5h-1.5z");
}

.lpshhqfzv {
  d: path("M4.5 3H21v18H3V3z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
