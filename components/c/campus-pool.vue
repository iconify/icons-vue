<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6wv9rfgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campus-pool" /></template>
<style>
.o6wv9rfgh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 14.5v-9a2.5 2.5 0 0 1 5 0m1.5 9v-9a2.5 2.5 0 0 1 5 0M6.5 9H13m-6.5 3H13M2.5 18.5q3-2.25 6 0t6 0t6 0");
}

</style>
