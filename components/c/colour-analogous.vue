<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fre04igyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colour-analogous" /></template>
<style>
.fre04igyt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 13.75a9.5 9.5 0 0 1 17.5 0l-4.5 2a4.5 4.5 0 0 0-8.5 0Zm5-5l2 4.5m5.5-4.5l-2 4.5");
}

</style>
