<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7e_jsb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camp-booties" /></template>
<style>
.z7e_jsb8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 3.5q2.25 1.5 4.5 0V12c2.25.25 3.5 2 3.5 4.5v2a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2Zm-3 0Q8.25 5 6 3.5V12c-2.25.25-3.5 2-3.5 4.5v2a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2Zm3 4H18m-4.5 3H18m-12-3h4.5m-4.5 3h4.5");
}

</style>
