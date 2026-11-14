<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hep0iwm-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:line-height" /></template>
<style>
.hep0iwm-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 5.5h9.5M11 12h9.5M11 18.5h9.5M5.5 4v16M3.25 6.25L5.5 4l2.25 2.25m-4.5 11.5L5.5 20l2.25-2.25");
}

</style>
