<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxxk39b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flat-mop" /></template>
<style>
.rxxk39b0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 17.5h9.5A1.75 1.75 0 0 1 16 19.25A1.75 1.75 0 0 1 14.25 21h-9.5A1.75 1.75 0 0 1 3 19.25a1.75 1.75 0 0 1 1.75-1.75m2.25 0q2.5-4 5 0m-2.5-2L19.5 3");
}

</style>
