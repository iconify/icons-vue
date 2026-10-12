<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ij8kpdtsp"/><path class="h98aoib7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:festival-wristband-sharp" /></template>
<style>
.h98aoib7x {
  d: path("M9.25 15.5h5.5V21h-5.5zm1.5 2.75h2.5");
}

.ij8kpdtsp {
  d: path("M4 11a8 4.5 0 1 0 16 0a8 4.5 0 1 0-16 0Zm3-.5a5 1.5 0 1 1 10 0a5 1.5 0 1 1-10 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
