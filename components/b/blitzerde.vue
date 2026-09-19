<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m26j42blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blitzerde" /></template>
<style>
.m26j42blf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 20.35L7.75 30.44L4.48 42.49L24 28.72l19.5 13.77l-3.27-12Zm0-8.58L11.13 18L9 25.59l15-8.73l15 8.73L36.87 18Zm0-6.27L13.34 9.9L11.9 15L24 9.27L36.1 15l-1.44-5.1Z");
}

</style>
