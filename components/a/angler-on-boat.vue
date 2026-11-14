<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0oxu9umm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:angler-on-boat" /></template>
<style>
.i0oxu9umm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13.5h14a1.25 1.25 0 0 1 1 2l-.975 1.3a1.75 1.75 0 0 1-1.4.7H6.375a1.75 1.75 0 0 1-1.4-.7L4 15.5a1.25 1.25 0 0 1 1-2m1.25-8a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M8 8.75v4.75m0-3l3.5.5m-1 2L19 3m0 0v8M3 21q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
