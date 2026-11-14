<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la2f6hbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ai-assistant-voice" /></template>
<style>
.la2f6hbrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0m9.25-4.5a7 7 0 0 1 0 9m-10.5-9a7 7 0 0 0 0 9m13-10.25a9.75 9.75 0 0 1 0 11.5M4.25 6.25a9.75 9.75 0 0 0 0 11.5");
}

</style>
