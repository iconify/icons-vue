<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvdfb6bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:freezer-burn" /></template>
<style>
.nvdfb6bap {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5v15M3.5 6.25l12.646 7.296M3.5 13.75l13-7.5m-8.5-3l2 2l2-2M14.75 5L14 7.5l2.75.75m0 3.5L14 12.5l.75 2.5M12 16.75l-2-2l-2 2M5.25 15L6 12.5l-2.75-.75m0-3.5L6 7.5L5.25 5M18.5 15c.25 1.5 3 2 3 4a2.75 2.75 0 0 1-5.5 0c0-1 .5-1.75 1-2.25c.25.75.75 1 1.25 1c0-1 0-2 .25-2.75");
}

</style>
