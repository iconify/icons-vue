<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ma526eqee"/><path class="bjacox7xx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cone-sharp" /></template>
<style>
.bjacox7xx {
  d: path("M4.25 17.5a8.5 3 0 0 1 15.5 0");
}

.ma526eqee {
  d: path("M10.9 3.6L12 1.62l1.1 1.98L20.5 18a8.5 3.25 0 0 1-17 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
