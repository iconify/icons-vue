<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n84z_xwzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:antenna-receive" /></template>
<style>
.n84z_xwzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 9.5v11m-2.5 0H13M9.5 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-3.479 4.178a6.5 6.5 0 0 1 0-8.356m9.958 0a6.5 6.5 0 0 1 0 8.356M18 14.5v7m-3-3l3 3l3-3");
}

</style>
