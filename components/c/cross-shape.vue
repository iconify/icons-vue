<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1sq49nhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cross-shape" /></template>
<style>
.p1sq49nhk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 2.5h3A1.5 1.5 0 0 1 15 4v1a1.5 1.5 0 0 0 1.5 1.5H18A1.5 1.5 0 0 1 19.5 8v3a1.5 1.5 0 0 1-1.5 1.5h-1.5A1.5 1.5 0 0 0 15 14v6a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 9 20v-6a1.5 1.5 0 0 0-1.5-1.5H6A1.5 1.5 0 0 1 4.5 11V8A1.5 1.5 0 0 1 6 6.5h1.5A1.5 1.5 0 0 0 9 5V4a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
