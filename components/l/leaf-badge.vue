<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f53u5ebvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-badge" /></template>
<style>
.f53u5ebvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.982 17.6c-1.939.757-4.193 1.15-6.732 1.15c0-9.5 5.5-15 15-15c0 5.12-1.598 9.078-4.558 11.64M3.75 20.25l1.5-1.5m0 0l8.25-8.25m1.25 7.5l2 2L21 15.75");
}

</style>
