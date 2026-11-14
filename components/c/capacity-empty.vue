<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj-lckb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:capacity-empty" /></template>
<style>
.vj-lckb1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8h9a3.5 3.5 0 0 1 3.5 3.5v1A3.5 3.5 0 0 1 15 16H6a3.5 3.5 0 0 1-3.5-3.5v-1A3.5 3.5 0 0 1 6 8m12.5 2H20a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 20 14h-1.5");
}

</style>
