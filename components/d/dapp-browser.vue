<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gl5r1muxd"/><path class="x_81gufuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dapp-browser" /></template>
<style>
.gl5r1muxd {
  d: path("M2.5 3h19v18h-19Zm0 5h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x_81gufuq {
  d: path("M7 11h10v7H7Zm5 0v7m-5-3.5h10");
}

</style>
