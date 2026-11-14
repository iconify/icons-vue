<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3hgnf1gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dewormer" /></template>
<style>
.r3hgnf1gu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.697 11.354l5.657-5.657a3.5 3.5 0 0 1 4.949 0a3.5 3.5 0 0 1 0 4.949l-5.657 5.657a3.5 3.5 0 0 1-4.949 0a3.5 3.5 0 0 1 0-4.949m2.828-2.829l4.95 4.95M15.25 19.5c.75-3 2.75-3 3.25-1s2.5 2 3.25-1");
}

</style>
