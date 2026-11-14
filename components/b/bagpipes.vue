<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klxz86d8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bagpipes" /></template>
<style>
.klxz86d8b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15.5a6.5 5 0 1 0 13 0a6.5 5 0 1 0-13 0M7.5 11l5-8M11 10.75l5-8m-1.5 9.5l5-8M4.5 12l-2-3");
}

</style>
