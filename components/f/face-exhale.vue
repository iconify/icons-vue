<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb5s8hm2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:face-exhale" /></template>
<style>
.mb5s8hm2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 21.5v-3.75c-2.75-1.5-4.25-4.25-4.25-7.5c0-4.5 3.25-7.75 7.5-7.75c3.25 0 5 2.25 5.25 5l1.5 3h-1.5V12l-2.25 1l2.25 1v1.25c0 1.25-.75 2-2.25 2H12v4.25M11 8h.01m6.74 5.5c1.25-1.25 2.5 1.25 3.75 0m-3.75 3c1.25-1.25 2.5 1.25 3.75 0");
}

</style>
