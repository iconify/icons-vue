<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuyplqbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bucket" /></template>
<style>
.iuyplqbqf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 8.75h15.5l-1.6 11a1.75 1.75 0 0 1-1.73 1.5H7.58a1.75 1.75 0 0 1-1.73-1.5ZM5.5 7c0-2.75 3-4.25 6.5-4.25s6.5 1.5 6.5 4.25M4.76 12.25h14.48");
}

</style>
