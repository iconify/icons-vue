<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-q18mbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blue-jay" /></template>
<style>
.e-q18mbgp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 20.75L8 15.5c0-4 2-6.5 4.5-7l-1-5.5l4 3c1 .5 1.5 1.5 1.5 2.5l3 1l-3 1c0 3.5-2 6-6 6.5l-4.5 4.25Zm8-.5h8m-5.5-11h.01");
}

</style>
