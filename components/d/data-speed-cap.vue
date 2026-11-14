<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynaxtibxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-speed-cap" /></template>
<style>
.ynaxtibxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.25 13.75a8.5 8.5 0 1 1 16.5 0M10.5 11.5L15.75 9m-5.25 2.5h.01m3.99 8H19m-2-2l2 2l-2 2m4.5-5V22");
}

</style>
