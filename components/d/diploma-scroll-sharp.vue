<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qszyen2ww"/><circle class="uvdixnb6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:diploma-scroll-sharp" /></template>
<style>
.qszyen2ww {
  d: path("M3.75 5.5h16.5v12H3.75zm0-1.25v14.5m16.5-14.5v14.5M7 8.5h10m-10 3h5.5");
}

.uvdixnb6r {
  cx: 15.25px;
  cy: 13.25px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
