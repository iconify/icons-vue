<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf8ldkbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:adaptive-spoon" /></template>
<style>
.uf8ldkbxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 7a3 4.5 0 1 0 6 0a3 4.5 0 1 0-6 0m-.25 3.25l-1.75 3.5m-.068.068za2.25 2.25 0 0 1 0 3.182L8.25 20.182a2.25 2.25 0 0 1-3.182 0a2.25 2.25 0 0 1 0-3.182l3.182-3.182a2.25 2.25 0 0 1 3.182 0");
}

</style>
