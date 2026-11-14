<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wag2yxudr"/><path class="h76uqy0ft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:broadcast-tower" /></template>
<style>
.h76uqy0ft {
  d: path("M10.5 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-1.25 8.5h5.5m1.08-11.714a5 5 0 0 1 0 6.428m-7.66 0a5 5 0 0 1 0-6.428");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wag2yxudr {
  d: path("m6.5 21.5l5.5-14l5.5 14");
}

</style>
