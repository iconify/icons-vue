<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdy80l8cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:architect-scale" /></template>
<style>
.sdy80l8cx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.515 6.371l6.217 10.753a1.75 1.75 0 0 1-1.515 2.626H5.783a1.75 1.75 0 0 1-1.515-2.626l6.217-10.753a1.75 1.75 0 0 1 3.03 0M9 19.75v-3m3 3v-5m3 5v-3");
}

</style>
