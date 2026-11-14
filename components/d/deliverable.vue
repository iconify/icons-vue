<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ru5jm4d0z"/><path class="segm6mgwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deliverable" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ru5jm4d0z {
  d: path("M5.5 3.5h13A2.5 2.5 0 0 1 21 6a2.5 2.5 0 0 1-2.5 2.5h-13A2.5 2.5 0 0 1 3 6a2.5 2.5 0 0 1 2.5-2.5m-1 5v10a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2v-10");
}

.segm6mgwt {
  d: path("m8.5 14l2.5 2.5l4.5-4.5");
}

</style>
