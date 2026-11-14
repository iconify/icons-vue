<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je-qxplkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dumbbell-off" /></template>
<style>
.je-qxplkh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 4.5zA1.75 1.75 0 0 1 8 6.25v8.5a1.75 1.75 0 0 1-1.75 1.75a1.75 1.75 0 0 1-1.75-1.75v-8.5A1.75 1.75 0 0 1 6.25 4.5m11.5 0za1.75 1.75 0 0 1 1.75 1.75v8.5a1.75 1.75 0 0 1-1.75 1.75A1.75 1.75 0 0 1 16 14.75v-8.5a1.75 1.75 0 0 1 1.75-1.75m-15.25 6h2m3.5 0h8m3.5 0h2M3 3l18 18");
}

</style>
