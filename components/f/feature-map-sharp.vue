<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="h4or-zwdo"/><path class="dw_f01qwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:feature-map-sharp" /></template>
<style>
.dw_f01qwq {
  d: path("M8.75 8.75h12.5v12.5H8.75zm6.25 0v12.5M8.75 15h12.5");
}

.h4or-zwdo {
  d: path("M2.75 14.75v-12h12M5.75 18V5.75H18");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
