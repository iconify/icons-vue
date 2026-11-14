<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcx5gdcit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fretboard" /></template>
<style>
.lcx5gdcit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.25 21.25l11-11L17 11l4.25-4.25l-4-4L13 7l.75.75l-11 11Zm.5-5.5l2.5 2.5m.5-5.5l2.5 2.5m.5-5.5l2.5 2.5m4.5-3L20 10.5m-4.25-6.25L14.5 3");
}

</style>
