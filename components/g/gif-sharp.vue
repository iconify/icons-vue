<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bicgcfb5m"/><path class="d472zr3hm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gif-sharp" /></template>
<style>
.bicgcfb5m {
  d: path("M2.75 5.75h18.5v12.5H2.75z");
}

.d472zr3hm {
  d: path("M9.27 10.23A2.5 2.5 0 1 0 10 12H8.25m4.5-2.5v5m2.75 0v-5h3m-3 2.5h2.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
