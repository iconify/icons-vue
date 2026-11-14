<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnsavjbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hedge-trimmer-pole" /></template>
<style>
.fnsavjbta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 21l6.25-6.25m-.018-2.104l1.414-1.414a1.5 1.5 0 0 1 2.122 0a1.5 1.5 0 0 1 0 2.122l-1.414 1.414a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122m3.518-1.396L20.5 3.5m-7.25 4.25l3 3m-.5-5.5l3 3m-.5-5.5l3 3");
}

</style>
