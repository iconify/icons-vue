<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="a2e82zb4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jupiter-sharp" /></template>
<style>
.a2e82zb4r {
  d: path("M5.25 8.25h13.5M4.75 12h5m-4.5 3.75h13.5M11.5 12a2.5 1.5 0 1 0 5 0a2.5 1.5 0 1 0-5 0Z");
}

.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
