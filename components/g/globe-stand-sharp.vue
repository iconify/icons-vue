<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="pxuq53uoo"/><path class="vslm1fbnj"/><path class="nuw0c_b9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:globe-stand-sharp" /></template>
<style>
.nuw0c_b9t {
  d: path("M16.8 3.68a8.25 8.25 0 0 1-9.42 13.46m4.12 1.11v3m-3.5 0h7");
}

.pxuq53uoo {
  cx: 11.5px;
  cy: 10px;
  r: 5.75px;
}

.vslm1fbnj {
  d: path("M5.75 10h11.5M11.5 4.25C10 6 9.25 7.85 9.25 10s.75 4 2.25 5.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
