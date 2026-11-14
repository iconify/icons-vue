<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kl7wh4b1s"/><path class="jho0ycc3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:food-waste-caddy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jho0ycc3d {
  d: path("M8.75 18.25c0-4 2.5-5.5 6.5-5.5c0 4-2.5 5.5-6.5 5.5m0 0l3.5-3.5");
}

.kl7wh4b1s {
  d: path("M5 7h14a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 19 10H5a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 5 7m1.5 0c0-4.5 11-4.5 11 0M5 10l1 10q.1 1 1 1h10q.9 0 1-1l1-10");
}

</style>
