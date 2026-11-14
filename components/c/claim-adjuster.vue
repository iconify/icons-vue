<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez32imb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:claim-adjuster" /></template>
<style>
.ez32imb2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 5.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M3.5 21.5v-2c0-3 1.75-4.75 4-5.5m13 7.5v-2c0-3-1.75-4.75-4-5.5m-6.375-2h3.75a2.625 2.625 0 0 1 2.625 2.625v4.25a2.625 2.625 0 0 1-2.625 2.625h-3.75A2.625 2.625 0 0 1 7.5 18.875v-4.25A2.625 2.625 0 0 1 10.125 12M10 12v-1.25h4V12m-3.75 4.75h3.5");
}

</style>
