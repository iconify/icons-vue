<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrjh4_b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:curling-hack" /></template>
<style>
.yrjh4_b5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19v-4c0-3.5 2-5 6.5-5s6.5 1.5 6.5 5v4m-9-9V6.5A1.5 1.5 0 0 1 8.5 5H14M2.5 19h19m-2-5v5");
}

</style>
