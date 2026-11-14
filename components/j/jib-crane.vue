<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz8bj6b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jib-crane" /></template>
<style>
.iz8bj6b5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5h6m-3 0v-19m0 1.5h14m-14 5.5l5-5.5m5 0v7.5m-2.5 3l2.5-3l2.5 3m-4.25 0h3.5A1.75 1.75 0 0 1 20 16.25v2.5a1.75 1.75 0 0 1-1.75 1.75h-3.5A1.75 1.75 0 0 1 13 18.75v-2.5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
