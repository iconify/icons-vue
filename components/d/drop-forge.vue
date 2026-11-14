<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acuwzhb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drop-forge" /></template>
<style>
.acuwzhb0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.106 15.5H6.5V13H8v-2.5q0-3-5.5-5v-2h17V7H17q-3 .5-3 3.5V13h1.194M18 14.5v7m-3-3l3 3l3-3");
}

</style>
