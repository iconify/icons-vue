<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw-p4rb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-mode-selector" /></template>
<style>
.vw-p4rb6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 14.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0m6 0V11m0-7.25v2m-7.5 4.5l-1.75-1m16.75 1l1.75-1");
}

</style>
