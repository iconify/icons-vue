<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xequ4ex2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:battery-swap-station" /></template>
<style>
.xequ4ex2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 3h5.75A2.625 2.625 0 0 1 13.5 5.625v.75A2.625 2.625 0 0 1 10.875 9h-5.75A2.625 2.625 0 0 1 2.5 6.375v-.75A2.625 2.625 0 0 1 5.125 3M15.5 5v2m-3.375 8h4.75a2.625 2.625 0 0 1 2.625 2.625v.75A2.625 2.625 0 0 1 16.875 21h-4.75A2.625 2.625 0 0 1 9.5 18.375v-.75A2.625 2.625 0 0 1 12.125 15m9.375 2v2m-2-15.5V11m-2-2l2 2l2-2m-17 11.5V13m-2 2l2-2l2 2");
}

</style>
