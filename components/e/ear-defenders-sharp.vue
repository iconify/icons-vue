<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zdy7-611b"/><path class="ohcjvuwxz"/><path class="xt51qgbyr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ear-defenders-sharp" /></template>
<style>
.ohcjvuwxz {
  d: path("M4.25 10.8a7.75 7.75 0 0 1 15.5 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xt51qgbyr {
  d: path("M7.25 10.8a4.75 4.75 0 0 1 9.5 0");
}

.zdy7-611b {
  d: path("M2.75 10.5h5.5v10.75h-5.5zm13 0h5.5v10.75h-5.5z");
}

</style>
