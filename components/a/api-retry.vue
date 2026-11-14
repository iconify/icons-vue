<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vx_h-ju3c"/><path class="t7j_8-bdw"/><path class="r11s8kbqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-retry" /></template>
<style>
.r11s8kbqb {
  d: path("m19.5 11.75l-2 2l2 2");
}

.t7j_8-bdw {
  d: path("m2.5 6l7 3.5l7-3.5m-7 3.5v7m8-2.75a3.75 3.75 0 1 1-3.75 3.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vx_h-ju3c {
  d: path("M10.978 15.761L9.5 16.5l-7-3.5V6l7-3.5l7 3.5v4.774m-2.481 3.466l-.984.492");
}

</style>
