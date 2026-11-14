<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p03gmbb3q"/><path class="znc2kx7qr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drainage-ditch" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p03gmbb3q {
  d: path("M2 6.5h3l2.75 12h8.5L19 6.5h3");
}

.znc2kx7qr {
  d: path("M8.75 10.25q1.625-1.5 3.25 0t3.25 0m-5.5 4.5q1.125-1.5 2.25 0t2.25 0");
}

</style>
