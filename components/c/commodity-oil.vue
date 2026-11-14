<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z35q4xs_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:commodity-oil" /></template>
<style>
.z35q4xs_o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5h6a3.5 3.5 0 0 1 3.5 3.5v9A3.5 3.5 0 0 1 15 21H9a3.5 3.5 0 0 1-3.5-3.5v-9A3.5 3.5 0 0 1 9 5M8 5V3h3v2m-5.5 5.5h13m-13 5h13");
}

</style>
