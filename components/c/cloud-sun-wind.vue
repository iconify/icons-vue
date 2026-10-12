<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6f66dbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cloud-sun-wind" /></template>
<style>
.a6f66dbhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.61 14.28a2.84 2.84 0 0 1-.39-5.65a4.08 4.08 0 0 1 7.55-.98a3.19 3.19 0 0 1-.42 6.63ZM14.1 4.8A2.75 2.75 0 0 1 18 8.58M18.75 4l.89-.88m.22 4.98l1.21.32M2.75 17.5h14A1.75 1.75 0 1 1 15 19.25m-9.25 2h5");
}

</style>
