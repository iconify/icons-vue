<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9rvx9bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:galleon" /></template>
<style>
.m9rvx9bcp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11h3v4h16L19 20H5l-2.5-5Zm6-7H13q.75 3.5 0 7H8.5q.75-3.5 0-7M16 5h4.5q.75 3 0 6H16q.75-3 0-6m-5.25 6v4m7.5-4v4");
}

</style>
