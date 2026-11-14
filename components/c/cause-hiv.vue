<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqex4ub-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cause-hiv" /></template>
<style>
.cqex4ub-x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 20.5l8-10.5c1.5-2.5.75-6.75-2.5-6.75S8 7.5 9.5 10l.75 1M14 15.75l3.5 4.75");
}

</style>
