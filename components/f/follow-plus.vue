<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjtgpibyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:follow-plus" /></template>
<style>
.fjtgpibyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m-3 14c0-4 3.25-6.5 7.5-6.5c1.157 0 2.24.185 3.204.536M18 15v6m-3-3h6");
}

</style>
