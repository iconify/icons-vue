<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqk8vu3-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:device-cooling-down" /></template>
<style>
.cqk8vu3-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.95 13.25H3.5V3h15v10.2m-16 3.3h10.9m5.35-.5v5.5m-2.5-4.25l5 3m-5 0l5-3");
}

</style>
