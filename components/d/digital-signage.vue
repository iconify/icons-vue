<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3wpi3bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:digital-signage" /></template>
<style>
.v3wpi3bzv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5h5A3.5 3.5 0 0 1 18 6v7a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 6 13V6a3.5 3.5 0 0 1 3.5-3.5m2.5 14v5m-4 0h8m-7-12h6");
}

</style>
