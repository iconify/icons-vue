<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j125ac4uy"/><path class="o7gb6m9ml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arch-pointed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j125ac4uy {
  d: path("M5.625 3h12.75A2.625 2.625 0 0 1 21 5.625v12.75A2.625 2.625 0 0 1 18.375 21H5.625A2.625 2.625 0 0 1 3 18.375V5.625A2.625 2.625 0 0 1 5.625 3");
}

.o7gb6m9ml {
  d: path("M8.5 21v-8A7 7 0 0 1 12 7a7 7 0 0 1 3.5 6v8");
}

</style>
