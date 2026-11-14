<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qypvnhy5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:carbon-sink" /></template>
<style>
.qypvnhy5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8.5a7.5 6 0 1 0 15 0a7.5 6 0 1 0-15 0m7.5 13v-7m7.5 0v7m-3-3l3 3l3-3");
}

</style>
