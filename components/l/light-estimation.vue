<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h82nyx9tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:light-estimation" /></template>
<style>
.h82nyx9tq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 8.5a3.5 3.5 0 0 1 7 0Zm-5 0h2.25m12.5 0h2.25M6.75 3.25l1 1m9.5-1l-1 1m-6.75 7L6.5 16m8-4.75l3 4.75M5 16h16.5L19 20.5H2.5Z");
}

</style>
