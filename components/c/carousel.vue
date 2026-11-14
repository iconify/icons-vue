<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw0kuubeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:carousel" /></template>
<style>
.uw0kuubeu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 3.5h3A3.5 3.5 0 0 1 17 7v5a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 7 12V7a3.5 3.5 0 0 1 3.5-3.5m-8 2h1.75v8H2.5m19-8h-1.75v8h1.75M9 19.5h.01m2.99 0h.01m2.99 0h.01");
}

</style>
