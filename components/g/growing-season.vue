<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuq-xjb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:growing-season" /></template>
<style>
.cuq-xjb2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10.5h18m-13.5 0a4.5 4.5 0 0 1 9 0M7 5.5L5.25 3.75M17 5.5l1.75-1.75M12 14v7m0-2c0-2-1.25-3.5-4-3.5c0 2.25 1.5 3.5 4 3.5m0-1.5c0-2 1.25-3.5 4-3.5c0 2.25-1.5 3.5-4 3.5");
}

</style>
