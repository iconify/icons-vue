<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzhe-muzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anchor-handler" /></template>
<style>
.fzhe-muzv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 3.5h3a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 9.75 9h-3A1.75 1.75 0 0 1 5 7.25v-2A1.75 1.75 0 0 1 6.75 3.5m8.998 10H5L2.5 9h19l-1.068 1.923M18.5 13v8.5m-3-3a3 3 0 0 0 6 0m-4.5-2h3");
}

</style>
