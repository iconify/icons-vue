<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9h961bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:avatar-placeholder" /></template>
<style>
.g9h961bbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.541 2.824a9.5 9.5 0 0 1 4.918 0m4.259 2.458a9.5 9.5 0 0 1 2.458 4.259m0 4.918a9.5 9.5 0 0 1-2.458 4.259m-4.259 2.458a9.5 9.5 0 0 1-4.918 0m-4.259-2.458a9.5 9.5 0 0 1-2.458-4.259m0-4.918a9.5 9.5 0 0 1 2.458-4.259M9 10a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-2 7.5c1-1.75 2.75-2.5 5-2.5s4 .75 5 2.5");
}

</style>
