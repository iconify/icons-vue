<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j2yj2kbts"/><path class="zdqjytzem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fishing-net-landing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j2yj2kbts {
  d: path("M3 7a6.5 3.5 0 1 0 13 0A6.5 3.5 0 1 0 3 7");
}

.zdqjytzem {
  d: path("M3 7.5C3.5 14 6.5 18 9.5 18s6-4 6.5-10.5m-.75 2.5L21 20.5m-11.5-10v7m-5-4.5h10");
}

</style>
