<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6c90ecsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chimney-smoke" /></template>
<style>
.z6c90ecsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 21.5l1.5-11h4l1.5 11ZM6.125 8.25h3.75A1.125 1.125 0 0 1 11 9.375A1.125 1.125 0 0 1 9.875 10.5h-3.75A1.125 1.125 0 0 1 5 9.375A1.125 1.125 0 0 1 6.125 8.25M8.75 4a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m4.5 1a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M18 7a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 18 7");
}

</style>
