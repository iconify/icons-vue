<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxhqlo-jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gum-disease" /></template>
<style>
.bxhqlo-jo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 10C4.75 7 5 2.75 8.5 2.75c1.5 0 2.25 1 3.5 1s2-1 3.5-1C19 2.75 19.25 7 17.75 10M4 10h16c0 3.5-3 6-8 6s-8-2.5-8-6m5 5.5l1 5.75m5-5.75l-1 5.75");
}

</style>
