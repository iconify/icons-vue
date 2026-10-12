<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvdt08l6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:freezing-rain" /></template>
<style>
.fvdt08l6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.51 13.89a3.52 3.52 0 0 1-.49-7.01a5.06 5.06 0 0 1 9.38-1.22a3.96 3.96 0 0 1-.53 8.23Zm.99 2.86L7.75 19m4.75-2.25L11.75 19m4.75-2.25L15.75 19m-13 2.25h18.5");
}

</style>
