<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pelwnvbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bed-check" /></template>
<style>
.pelwnvbin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3v15.5m0-9h16a2 2 0 0 1 2 2V13H3m4.5-7.5h1a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 8.5 9.5h-1a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 7.5 5.5M14.75 18l2 2L21 15.75");
}

</style>
