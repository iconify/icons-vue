<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9hpoqy2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:day-night-cycle" /></template>
<style>
.j9hpoqy2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 6a6 6 0 0 0 0 12Zm0 0a6 6 0 0 1 0 12a8 8 0 0 0 0-12M3 12h2.25m2.5-6.25l-1.5-1.5m1.5 14l-1.5 1.5");
}

</style>
