<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erxp2lg2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drop-forge" /></template>
<style>
.erxp2lg2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.206 15.5H6.5V13H8v-2.5q0-3-5.5-5v-2h17V7H17q-3 .5-3 3.5V13h1.5v.294M18 14.5v7m-3-3l3 3l3-3");
}

</style>
