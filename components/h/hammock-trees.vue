<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztm89wqei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hammock-trees" /></template>
<style>
.ztm89wqei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m3.5 3.5v12M15 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m3.5 3.5v12M5.5 11l3 3.5q3.5 6.5 7 0l3-3.5m-10 3.5h7");
}

</style>
