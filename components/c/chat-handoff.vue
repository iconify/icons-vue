<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6j9uglqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chat-handoff" /></template>
<style>
.l6j9uglqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h4a2.5 2.5 0 0 1 2.5 2.5V8A2.5 2.5 0 0 1 9 10.5H6l-3.25 2.75V5.5A2.5 2.5 0 0 1 5 3m10 8h4a2.5 2.5 0 0 1 2.5 2.5v7.25l-3.25-2.25H15a2.5 2.5 0 0 1-2.5-2.5v-2.5A2.5 2.5 0 0 1 15 11m-.75-5.5h6.25M18 3l2.5 2.5L18 8");
}

</style>
