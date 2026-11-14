<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy9n_nbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-dolly" /></template>
<style>
.vy9n_nbkv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.625 7.5h4.75A2.625 2.625 0 0 1 14 10.125v2.25A2.625 2.625 0 0 1 11.375 15h-4.75A2.625 2.625 0 0 1 4 12.375v-2.25A2.625 2.625 0 0 1 6.625 7.5M4.5 7.5a2.5 2.5 0 1 1 4.25 0a2.5 2.5 0 1 1 4.25 0m2.026 1.158l1.5-.5A1.5 1.5 0 0 1 18.5 9.581v.743a1.5 1.5 0 0 1-1.666 1.491l-1.592-.177A1.397 1.397 0 0 1 14 10.25v-.169a1.5 1.5 0 0 1 1.026-1.423M2.5 15h19M5 19.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m11 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
