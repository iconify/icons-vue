<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6o6wnkyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cufflinks" /></template>
<style>
.r6o6wnkyd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 6.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M7 9.75v5M4.25 17.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m9.5-11a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M17 9.75v5m-2.75 2.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

</style>
