<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo4mhdi7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dive-alpha-flag" /></template>
<style>
.uo4mhdi7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 4h10.4a1.394 1.394 0 0 1 1.1 2.25l-.914 1.176a1.75 1.75 0 0 0 0 2.148l.914 1.176a1.394 1.394 0 0 1-1.1 2.25H6.75A1.75 1.75 0 0 1 5 11.25v-5.5A1.75 1.75 0 0 1 6.75 4M5 3v18.5M11.5 4v9");
}

</style>
