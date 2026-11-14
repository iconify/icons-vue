<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1lbqnfsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:airport-check-in-desk" /></template>
<style>
.m1lbqnfsx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h19M4 13v8.5h16V13M13.625 3h3.75A2.625 2.625 0 0 1 20 5.625v1.25A2.625 2.625 0 0 1 17.375 9.5h-3.75A2.625 2.625 0 0 1 11 6.875v-1.25A2.625 2.625 0 0 1 13.625 3M15.5 9.5V13");
}

</style>
