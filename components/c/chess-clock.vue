<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcmdgeb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chess-clock" /></template>
<style>
.rcmdgeb2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8h1a3.5 3.5 0 0 1 3.5 3.5v3A3.5 3.5 0 0 1 7 18H6a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 6 8m11 0h1a3.5 3.5 0 0 1 3.5 3.5v3A3.5 3.5 0 0 1 18 18h-1a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 17 8M5.25 5h2.5a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 7.75 8h-2.5a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 5.25 5m11 0h2.5a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-2.5a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5M6.5 13.5v-2.75m0 2.75l1.25 1m9.75-1v-2.75m0 2.75l-1.25 1");
}

</style>
