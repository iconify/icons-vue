<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szjeb-fop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fireworks-finale" /></template>
<style>
.szjeb-fop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 7h2.75M5.5 7H2.75M7 5.5V2.75M7 8.5v2.75M8 6l2-2M6 6L4 4m4 4l2 2M6 8l-2 2m14.75-1.5H21m-4.75 0H14m3.5-1.25V5m0 4.75V12m1-4.5L20 6m-3.5 1.5L15 6m3.5 3.5L20 11m-3.5-1.5L15 11M9.5 21.5Q9 17 7.5 14m7 7.5q1-3.75 3-6.75");
}

</style>
