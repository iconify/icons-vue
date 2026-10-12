<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsbq9sb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kite-spool" /></template>
<style>
.qsbq9sb4w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 8h7.5v8h-7.5Zm1.25 2l5 4m-5 0l5-4m-9.75 2a1.75 6 0 1 0 3.5 0a1.75 6 0 1 0-3.5 0m11 0a1.75 6 0 1 0 3.5 0a1.75 6 0 1 0-3.5 0m-13 0h2m14.5 0h2");
}

</style>
