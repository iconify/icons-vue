<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tq6lj7bhl"/><path class="nkda28rnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:launch-tower" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nkda28rnc {
  d: path("M3.5 7L8 11.5L3.5 16M8 6.5h4.5");
}

.tq6lj7bhl {
  d: path("M3.5 21V3H8v18m7-18c2.5 2 3 5 3 8v7h-6v-7c0-3 .5-6 3-8M2.5 21h19");
}

</style>
