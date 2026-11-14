<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfpo98gkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lever" /></template>
<style>
.rfpo98gkb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 9.5l18 6m-7.658-.317l1.073 2.146a1.5 1.5 0 0 1-1.342 2.171h-2.146a1.5 1.5 0 0 1-1.342-2.171l1.073-2.146a1.5 1.5 0 0 1 2.684 0M4.75 3.5h1A1.5 1.5 0 0 1 7.25 5v1a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 3.25 6V5a1.5 1.5 0 0 1 1.5-1.5M19 3.5V10m-2-2l2 2l2-2");
}

</style>
