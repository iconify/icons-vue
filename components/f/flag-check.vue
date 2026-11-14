<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4y7akbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flag-check" /></template>
<style>
.m4y7akbtq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 4h9.649A1.348 1.348 0 0 1 17.5 6.125l-.766 1.085a1.75 1.75 0 0 0 .03 2.059l.736.981a1.25 1.25 0 0 1-1 2H6.75A1.75 1.75 0 0 1 5 10.5V5.75A1.75 1.75 0 0 1 6.75 4M5 3v18m9.75-3l2 2L21 15.75");
}

</style>
