<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="clg7v8flh"/><path class="xalax7ehx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:da-capo" /></template>
<style>
.clg7v8flh {
  d: path("M14 17v-7a4 4 0 0 0-8 0v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xalax7ehx {
  d: path("M3.5 13.5L6 16l2.5-2.5m9-9.5v16m3-16v16");
}

</style>
