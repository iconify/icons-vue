<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6jsm4bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:irish-coffee-glass" /></template>
<style>
.w6jsm4bzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3.5h8.5V11a4 4 0 0 1-4 4H10a4 4 0 0 1-4-4Zm8.5 2H16a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-1.5M10.25 15v5.5M7 20.5h6.5M6 7h8.5");
}

</style>
