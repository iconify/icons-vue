<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_qzmbcqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:display-light-spot" /></template>
<style>
.c_qzmbcqy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19m-9.5 0v2.25m-1.283 0h2.566a1.5 1.5 0 0 1 1.468 1.191l.368 1.75A1.5 1.5 0 0 1 13.651 9.5h-3.302a1.5 1.5 0 0 1-1.468-1.809l.368-1.75a1.5 1.5 0 0 1 1.468-1.191M8.5 12l-4.25 7.5M15.5 12l4.25 7.5m-15.5 0a7.75 2 0 1 0 15.5 0a7.75 2 0 1 0-15.5 0");
}

</style>
