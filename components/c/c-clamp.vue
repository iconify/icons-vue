<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsyif-jng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:c-clamp" /></template>
<style>
.lsyif-jng {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 4h-7a4.5 4.5 0 0 0-4.5 4.5v7A4.5 4.5 0 0 0 10 20h7m0-17.5V13m-2 0h4M15 2.5h4M15 20h4");
}

</style>
