<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5imkdsos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aisle-blocked" /></template>
<style>
.m5imkdsos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h1.5A1.5 1.5 0 0 1 7 4v16a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 20V4A1.5 1.5 0 0 1 4 2.5m14.5 0H20A1.5 1.5 0 0 1 21.5 4v16a1.5 1.5 0 0 1-1.5 1.5h-1.5A1.5 1.5 0 0 1 17 20V4a1.5 1.5 0 0 1 1.5-1.5m-10 7.25h7a1.5 1.5 0 0 1 1.5 1.5v1.5a1.5 1.5 0 0 1-1.5 1.5h-7a1.5 1.5 0 0 1-1.5-1.5v-1.5a1.5 1.5 0 0 1 1.5-1.5M7 5.5h2.25M7 18.5h2.25M17 5.5h-2.25m2.25 13h-2.25M9 14.25l2.25-4.5m1.5 4.5L15 9.75");
}

</style>
