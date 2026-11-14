<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx20c88sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:credit-card-scan" /></template>
<style>
.dx20c88sj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8V6A2.5 2.5 0 0 1 6 3.5h2m8 0h2A2.5 2.5 0 0 1 20.5 6v2m0 8v2a2.5 2.5 0 0 1-2.5 2.5h-2m-8 0H6A2.5 2.5 0 0 1 3.5 18v-2m6.125-8h4.75A2.625 2.625 0 0 1 17 10.625v2.75A2.625 2.625 0 0 1 14.375 16h-4.75A2.625 2.625 0 0 1 7 13.375v-2.75A2.625 2.625 0 0 1 9.625 8M7 10.75h10");
}

</style>
