<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivv83s7ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lifeboat" /></template>
<style>
.ivv83s7ha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.5 12.25l-7-8.5m-4.75 5.5q1.75 3 6.25 3h6q4.5 0 6.25-3q-.75 9.5-4.25 9.5H7q-3.5 0-4.25-9.5M6.5 15.5h11");
}

</style>
