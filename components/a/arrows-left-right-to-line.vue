<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoxjt6b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrows-left-right-to-line" /></template>
<style>
.uoxjt6b0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h6.25M5.5 9l3.25 3l-3.25 3m16-3h-6.25m3.25-3l-3.25 3l3.25 3M12 4v16");
}

</style>
