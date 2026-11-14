<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z8mrp0beg"/><path class="mi9_r5aqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delivery-neighbor" /></template>
<style>
.mi9_r5aqd {
  d: path("M5.25 14h3.5v6.5h-3.5Zm9 1.25h7.5v6.5h-7.5Zm3.75 0V18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z8mrp0beg {
  d: path("M11.436 20.5H2.5V9.75L7 5l4.5 4.75v2.714m2.75.002V8L18 4l3.75 4v4.434");
}

</style>
