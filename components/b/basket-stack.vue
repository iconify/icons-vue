<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svkpv5h9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basket-stack" /></template>
<style>
.svkpv5h9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3.5h14l-1.25 5h2.75L19 14h2.5l-2 7.5h-15l-2-7.5H5L3.5 8.5h2.75Zm1.25 5h11.5M5 14h14m-9.5 0v7.5m5-7.5v7.5");
}

</style>
