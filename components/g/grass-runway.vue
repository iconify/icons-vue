<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkw8c34gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grass-runway" /></template>
<style>
.jkw8c34gg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 4h15.5a1.75 1.75 0 0 1 1.75 1.75v4.5A1.75 1.75 0 0 1 19.75 12H4.25a1.75 1.75 0 0 1-1.75-1.75v-4.5A1.75 1.75 0 0 1 4.25 4M5.5 8H8m2.75 0h2.5M16 8h2.5m-16 12.5h19m-17 0q0-3-2-4.5m2 4.5q0-3 2-4.5m5.5 4.5q0-3-2-4.5m2 4.5q0-3 2-4.5m5.5 4.5q0-3-2-4.5m2 4.5q0-3 2-4.5");
}

</style>
