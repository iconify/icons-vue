<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8jwszlbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bridge-crane" /></template>
<style>
.v8jwszlbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19m-18 0v17m17-17v17M11 4h2a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 13 7h-2a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 11 4m1 3v6m0 0v2.5a2 2 0 1 1-2 2");
}

</style>
