<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x3mwnw_kp"/><path class="lv4o2fbtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cheat-code-sharp" /></template>
<style>
.lv4o2fbtj {
  d: path("M6.5 15.5v-7M5 10l1.5-1.5L8 10m4 5.5v-7M10.5 10L12 8.5l1.5 1.5m4-1.5v7M16 14l1.5 1.5L19 14");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x3mwnw_kp {
  d: path("M2.75 6h18.5v12H2.75z");
}

</style>
