<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fosmfdcqr"/><path class="a1us_nbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:7mind" /></template>
<style>
.a1us_nbwa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.304 41.408l9.334-17.347H17.146");
}

.fosmfdcqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.528 16.431V31.57a4.36 4.36 0 0 0 2.181 3.778l13.11 7.569a4.36 4.36 0 0 0 4.362 0l13.11-7.57a4.36 4.36 0 0 0 2.181-3.777V16.43a4.36 4.36 0 0 0-2.18-3.778l-13.11-7.569a4.36 4.36 0 0 0-4.363 0l-13.11 7.57a4.36 4.36 0 0 0-2.18 3.777");
}

</style>
