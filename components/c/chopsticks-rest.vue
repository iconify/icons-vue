<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_-r_bbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chopsticks-rest" /></template>
<style>
.o_-r_bbqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 8.75l19-3m-19 6l19-3M8 13.5q4 1.5 8 0a2.5 2.5 0 0 1 0 5q-4-1.5-8 0a2.5 2.5 0 0 1 0-5");
}

</style>
