<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e26v9onpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:disease-alert" /></template>
<style>
.e26v9onpl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 17C3.69 9.94 7.81 5.81 15 5.75C14.94 12.94 10.81 17.06 3.75 17M2.5 18.25L3.75 17m0 0L10 11m10-6v8.5m0 4.5h.01");
}

</style>
