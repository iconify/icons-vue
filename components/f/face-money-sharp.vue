<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="s2nm2lbos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-money-sharp" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.s2nm2lbos {
  d: path("M10.5 8H7.25v2.5h3.5V13H7.5M9 7v1m0 5v1m7.5-6h-3.25v2.5h3.5V13H13.5M15 7v1m0 5v1m-6.25 2.5L10.1 18h3.8l1.35-1.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
