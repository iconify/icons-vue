<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwxm42y6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dry-season" /></template>
<style>
.xwxm42y6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 10.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m3.5-5.75v-2.5m0 14v2.5M4.75 10.5h-2.5m14 0h2.5M6.5 6.5L4.75 4.75M14.5 6.5l1.75-1.75M6.5 14.5l-1.75 1.75m12-.75h2.5A1.75 1.75 0 0 1 21 17.25v2.25a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.5v-2.25a1.75 1.75 0 0 1 1.75-1.75M15 17.75h6m-4.25-3.25V16m2.5-1.5V16");
}

</style>
