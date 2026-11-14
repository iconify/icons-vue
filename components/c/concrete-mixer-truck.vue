<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jianh4bcb"/><path class="tfyew8b-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:concrete-mixer-truck" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jianh4bcb {
  d: path("M2.5 15.5h19v-4l-3-3.5h-3v7.5");
}

.tfyew8b-a {
  d: path("M3.25 10.75a5 3.5-20 0 1 9.5-3.5a5 3.5-20 0 1-9.5 3.5M5 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
