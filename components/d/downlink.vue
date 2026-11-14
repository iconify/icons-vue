<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-97slb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:downlink" /></template>
<style>
.h-97slb7f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.318 9.025l.707-.707a1.75 1.75 0 0 1 2.475 0l3.182 3.182a1.75 1.75 0 0 1 0 2.475l-.707.707a1.75 1.75 0 0 1-2.475 0L8.318 11.5a1.75 1.75 0 0 1 0-2.475m-4.95 6.364l1.768-1.768a1.5 1.5 0 0 1 2.121 0l2.122 2.122a1.5 1.5 0 0 1 0 2.121l-1.768 1.768a1.5 1.5 0 0 1-2.121 0L3.368 17.51a1.5 1.5 0 0 1 0-2.121M13.621 5.136l1.768-1.768a1.5 1.5 0 0 1 2.121 0l2.122 2.122a1.5 1.5 0 0 1 0 2.121l-1.768 1.768a1.5 1.5 0 0 1-2.121 0l-2.122-2.122a1.5 1.5 0 0 1 0-2.121M8.25 14.75L10 13m3-3l1.75-1.75M4.25 14.5l4.25 4.25m6-14.5l4.25 4.25m-.75 6v7m-3-3l3 3l3-3");
}

</style>
