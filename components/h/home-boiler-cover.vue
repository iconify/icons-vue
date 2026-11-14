<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cc4mvj60u"/><path class="b9ti9wbvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-boiler-cover" /></template>
<style>
.b9ti9wbvo {
  d: path("M10.5 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM12 18c-1.75 0-3-1.1-3-2.5c0-1.75 2-2.5 2.25-4c1 .75 1.25 1.5 1.25 2.5c1-.5 1.5-1.25 1.75-2c.5 1 .75 2 .75 3.5c0 1.4-1.25 2.5-3 2.5Z");
}

.cc4mvj60u {
  d: path("M5.5 3.5h13v17h-13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
