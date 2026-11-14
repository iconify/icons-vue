<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4387yk1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:magnet-pickup" /></template>
<style>
.j4387yk1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 12.5V8a5.5 5.5 0 0 1 11 0v4.5H14V8a2 2 0 0 0-4 0v4.5Zm2.5 3h7.5a3 3 0 0 1 0 6h-9a1.5 1.5 0 0 1 0-3H15M6.5 10H10m4 0h3.5");
}

</style>
