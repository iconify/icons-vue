<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j7d3c-bzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:all-tools" /></template>
<style>
.j7d3c-bzl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.294 43.5c6.157-22.318 11.74-30.939 19.74-38.619c.912-.875 2.413-.136 2.27 1.12c-1.244 10.878 5.59 29.466 9.402 37.499");
}

</style>
