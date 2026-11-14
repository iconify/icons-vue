<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-fayx_yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:foghorn" /></template>
<style>
.u-fayx_yn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8.5H8l6-4v11l-6-4H3.5Zm2.5 3v8m-2.5 0h5m8.25-12.25a4 4 0 0 1 0 5.5M19 5a7 7 0 0 1 0 10");
}

</style>
