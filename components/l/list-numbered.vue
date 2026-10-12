<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf4lz5u3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:list-numbered" /></template>
<style>
.qf4lz5u3b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 6h10m-10 6h10m-10 6h10m-16-12.75L6 3.75v6.5m-2 5a1.75 1.75 0 1 1 3.25.9L4 20.25h3.75");
}

</style>
