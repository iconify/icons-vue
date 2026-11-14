<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txm1bdcsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clearance-rack" /></template>
<style>
.txm1bdcsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h19m-14 0v2m-2 .5h4L12 8l-1.25 1.5l-.75-.75V16H5V8.75l-.75.75L3 8Zm11-2.5v2m-2.201 8H14V8.75l-.75.75L12 8l2.5-2.5h4L21 8l-1.25 1.5l-.75-.75V13h-2.301m-1.949 8.25l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
