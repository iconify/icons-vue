<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs427cc5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:battery-aa" /></template>
<style>
.xs427cc5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 4.5h1A3.5 3.5 0 0 1 16 8v10a3.5 3.5 0 0 1-3.5 3.5h-1A3.5 3.5 0 0 1 8 18V8a3.5 3.5 0 0 1 3.5-3.5m0-2h1a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-1a1 1 0 0 1-1-1a1 1 0 0 1 1-1M8 8.5h8");
}

</style>
