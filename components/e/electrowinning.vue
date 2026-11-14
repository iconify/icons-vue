<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2unfn4au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electrowinning" /></template>
<style>
.m2unfn4au {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9v10.5A1.5 1.5 0 0 0 5 21h14a1.5 1.5 0 0 0 1.5-1.5V9M6 3.5h12M3.5 12h17M8 3.5v14m4-14v14m4-14v14");
}

</style>
