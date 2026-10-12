<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wesswhb0d"/><path class="mrx0_nsnu"/><circle class="jwdhipbso"/><path class="q_mj3bc9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:background-check-sharp" /></template>
<style>
.jwdhipbso {
  cx: 16.25px;
  cy: 16.25px;
  r: 3.5px;
}

.mrx0_nsnu {
  d: path("M11.75 7.5a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 1 1 3.5 0M7 13.25l.8-2h4.4l.8 2");
}

.q_mj3bc9y {
  d: path("m18.75 18.75l2.5 2.5");
}

.wesswhb0d {
  d: path("M3.75 2.75h12.5v17H3.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
