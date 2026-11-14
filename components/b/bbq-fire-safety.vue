<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug1b-pbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bbq-fire-safety" /></template>
<style>
.ug1b-pbvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.898 13.777A7.5 7.5 0 0 1 9.75 15c-4 0-7.25-3-7.25-7H17a6.83 6.83 0 0 1-1.81 4.68M4 5.25C5 3.5 7.25 2.5 9.75 2.5s4.75 1 5.75 2.75m-8.75 9.5V21m6-6.25v1.4m5.5 5.85c-2 0-3.25-1.5-3.25-3.25c0-1.5.75-2.5 1.25-3.5c.75.75 1 1.25 1 2.25c.75-1.25 1.25-2.5 1-3.75c2 1.25 3.25 3.25 3.25 5S20.25 22 18.25 22");
}

</style>
