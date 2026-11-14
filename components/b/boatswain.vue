<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpeqx0bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boatswain" /></template>
<style>
.wpeqx0bfv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6.5c0-3.75 8-3.75 8 0m-9.5 0h11M8.25 9.25a3.75 3.75 0 0 0 7.5 0M4.5 21.5c0-3 3.25-5.25 7.5-5.25q.684 0 1.33.076m4.42 2.174a1 1 0 0 1 2 0a2 2 0 0 1-4 0a3 3 0 0 1 6 0");
}

</style>
