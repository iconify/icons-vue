<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f4_j_7c9i"/><path class="p3z7sob_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:battery-warning-car" /></template>
<style>
.f4_j_7c9i {
  d: path("M2.5 6h19v15h-19Zm3 0V3.5H9V6m6 0V3.5h3.5V6");
}

.p3z7sob_x {
  d: path("m12 8.75l5.5 9.5h-11Zm0 3.5v2.5m0 1.75h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
