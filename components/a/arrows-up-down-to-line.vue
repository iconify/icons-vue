<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4oy8dbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrows-up-down-to-line" /></template>
<style>
.w4oy8dbny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v6.25M9 5.5l3 3.25l3-3.25m-3 16v-6.25M9 18.5l3-3.25l3 3.25M4 12h16");
}

</style>
