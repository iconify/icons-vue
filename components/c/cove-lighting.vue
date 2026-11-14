<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ks5z5peas"/><path class="hszjllbvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cove-lighting" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hszjllbvx {
  d: path("M3 14h8v-2M7 9.5L6 6m3.75 3.5l1-3.5m1.75 4l3-3");
}

.ks5z5peas {
  d: path("M21.5 3H3v18.5");
}

</style>
