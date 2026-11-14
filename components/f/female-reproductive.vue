<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz_kxebkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:female-reproductive" /></template>
<style>
.wz_kxebkj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9c0-1 1-1.5 3.5-1.5s3.5.5 3.5 1.5c0 3.5-1.5 6-2.25 7.5v4h-2.5v-4C10 15 8.5 12.5 8.5 9m0-.25C7 5.5 4.5 5 3.5 8m12 .75C17 5.5 19.5 5 20.5 8m-18 3.75a1.75 1.5 0 1 0 3.5 0a1.75 1.5 0 1 0-3.5 0m15.5 0a1.75 1.5 0 1 0 3.5 0a1.75 1.5 0 1 0-3.5 0");
}

</style>
