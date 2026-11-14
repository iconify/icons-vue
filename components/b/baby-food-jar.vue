<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd08yrbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-food-jar" /></template>
<style>
.hd08yrbwg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 3h10.5A1.75 1.75 0 0 1 19 4.75v1a1.75 1.75 0 0 1-1.75 1.75H6.75A1.75 1.75 0 0 1 5 5.75v-1A1.75 1.75 0 0 1 6.75 3M6.5 7.5V9q-2 1-2 3.5v6A2.5 2.5 0 0 0 7 21h10a2.5 2.5 0 0 0 2.5-2.5v-6q0-2.5-2-3.5V7.5M4.5 13h15m-15 4.5h15");
}

</style>
