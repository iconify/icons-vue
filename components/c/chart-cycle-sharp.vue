<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="oegkhubcv"/><path class="h75nsrmxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-cycle-sharp" /></template>
<style>
.h75nsrmxf {
  d: path("M18.5 3v3.75h-3.75M5.5 21v-3.75h3.75m-1-3.25l2.5-2.5l2 1.5l3-3.5");
}

.oegkhubcv {
  d: path("M20.25 12a8.25 8.25 0 0 1-14.5 5.4m-2-5.4a8.25 8.25 0 0 1 14.5-5.4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
