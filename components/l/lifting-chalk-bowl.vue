<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g83q7h7rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lifting-chalk-bowl" /></template>
<style>
.g83q7h7rq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18c0 5-4 8.5-9 8.5S3 16 3 11m3.5 0c1-5 3.5-7 5.5-7s4.5 2 5.5 7");
}

</style>
