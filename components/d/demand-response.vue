<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttbrf_b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:demand-response" /></template>
<style>
.ttbrf_b7y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 21.5l3.75-18h2.5l2.206 12.216M3 7h16M4.5 12h12.3m1.2 2.5v7m-3-3l3 3l3-3");
}

</style>
