<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_cjyobpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bullpen" /></template>
<style>
.l_cjyobpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21c4-5 15-5 19 0ZM9 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-2 8.5c0-1.75 2.25-2.75 5-2.75s5 1 5 2.75");
}

</style>
