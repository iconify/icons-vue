<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v7iyp0bxg"/><path class="m-fcvsb7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:belay-gloves" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-fcvsb7k {
  d: path("M6 18.5a5.5 2.5 0 1 0 11 0a5.5 2.5 0 1 0-11 0M16.25 20l3.25 1.5");
}

.v7iyp0bxg {
  d: path("M8 16.5v-3l-3.25-3.25a1.77 1.77 0 0 1 2.5-2.5L8 8.5v-2a3.5 3.5 0 0 1 7 0v10");
}

</style>
