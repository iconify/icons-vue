<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m42dr2blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lifeguard-tower-public" /></template>
<style>
.m42dr2blq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8L12 3l8.5 5Zm3 0v4.5h11V8M7 12.5l-2 9m12-9l2 9m-8.5-9v9m3-9v9m-3-5.75h3m-3 3h3");
}

</style>
