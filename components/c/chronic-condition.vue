<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ael3d9hhg"/><path class="bzi3zghbv"/><path class="r049e7eoz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chronic-condition" /></template>
<style>
.ael3d9hhg {
  d: path("M12 10.5h1.25c1 0 1.5.5 2 1.25l1 1.75c.5.5 0 1-.75 1c-.25 0-.75-.25-.75-.5L14 12.75l.25 1.5l.5 3q0 .75-.75.75h-.75c-.25 0-.5-.25-.5-.75L12.5 15c-.25-.5-.75-.5-1 0l-.25 2.25c0 .5-.25.75-.5.75H10q-.75 0-.75-.75l.5-3l.25-1.5L9.25 14c0 .25-.5.5-.75.5c-.75 0-1.25-.5-.75-1l1-1.75c.5-.75 1-1.25 2-1.25Zm-1.5-2.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.bzi3zghbv {
  d: path("M18.106 4.723a9.5 9.5 0 1 1-10.856-.95");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r049e7eoz {
  d: path("m14.25 2.5l3 2.25L15 7.5");
}

</style>
