<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asave1a5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-suction" /></template>
<style>
.asave1a5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 21.5v-11A4.5 4.5 0 0 1 9 6h3.5m1.041-1.585l4-1.285A1.5 1.5 0 0 1 19.5 4.558v2.884a1.5 1.5 0 0 1-1.959 1.428l-4-1.285A1.5 1.5 0 0 1 12.5 6.157v-.314a1.5 1.5 0 0 1 1.041-1.428M17 12.5C16 14 15 15 15 16a2 2 0 0 0 4 0c0-1-1-2-2-3.5");
}

</style>
