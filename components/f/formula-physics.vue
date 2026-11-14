<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbu2l_b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:formula-physics" /></template>
<style>
.hbu2l_b5c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12H13m-2.5-8.5H6.25v5.75m0-3H9.5M5.75 15L8 20.5l2.25-5.5M16 9.75h5m-5 4.5h5");
}

</style>
