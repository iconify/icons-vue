<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbr262bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cinema-screen" /></template>
<style>
.nbr262bcp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4q9.5-1.5 19 0v10.5q-9.5-1.5-19 0ZM5 21a3 3 0 0 1 6 0m2 0a3 3 0 0 1 6 0");
}

</style>
