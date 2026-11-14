<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kioyjwvsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:draw-search-area" /></template>
<style>
.kioyjwvsa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.375 18.375l.278-1.206a1.5 1.5 0 0 1 .401-.723l4.385-4.385a1.5 1.5 0 0 1 2.122 0l.378.378a1.5 1.5 0 0 1 0 2.122l-4.385 4.385a1.5 1.5 0 0 1-.723.401l-1.206.278a1.042 1.042 0 0 1-1.25-1.25m.375-1.625l2.5 2.5m2-7l2.5 2.5m-10.5 3.5L7.5 17M5 15.25L3 14l.25-2m.25-2l.25-2m.5-2l.25-2.5L7 3.25M9 3l2-.25m1.5 0L15 2.5l1.75 1.75m1.5 1.5l1.5 1.5");
}

</style>
