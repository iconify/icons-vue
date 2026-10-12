<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ephvlvbiw"/><circle class="wugx_cc9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hidden-camera-sharp" /></template>
<style>
.ephvlvbiw {
  d: path("M2.75 5.25h18.5m-17.5 3h16.5v1.5a8.25 8.25 0 0 1-16.5 0Z");
}

.wugx_cc9r {
  cx: 12px;
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
