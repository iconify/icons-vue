<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qe97cg-lx"/><path class="pj7tcibhm"/><path class="bgip2qess"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lap-chart" /></template>
<style>
.bgip2qess {
  d: path("M6.5 7h8v10.5h5");
}

.pj7tcibhm {
  d: path("M6.5 17.5H11V11h8.5");
}

.qe97cg-lx {
  d: path("M3 3v18h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
