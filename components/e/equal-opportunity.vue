<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcmnsib6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:equal-opportunity" /></template>
<style>
.fcmnsib6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5v19m6-19v19m5-19v19m6-19v19M3.5 7h6m-6 5h6m-6 5h6m5-10h6m-6 5h6m-6 5h6");
}

</style>
