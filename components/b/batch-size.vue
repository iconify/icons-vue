<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev672hbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:batch-size" /></template>
<style>
.ev672hbut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h8.5A1.75 1.75 0 0 1 15 4.5v.75A1.75 1.75 0 0 1 13.25 7h-8.5A1.75 1.75 0 0 1 3 5.25V4.5a1.75 1.75 0 0 1 1.75-1.75m0 7.25h8.5A1.75 1.75 0 0 1 15 11.75v.75a1.75 1.75 0 0 1-1.75 1.75h-8.5A1.75 1.75 0 0 1 3 12.5v-.75A1.75 1.75 0 0 1 4.75 10m0 7.25h8.5A1.75 1.75 0 0 1 15 19v.75a1.75 1.75 0 0 1-1.75 1.75h-8.5A1.75 1.75 0 0 1 3 19.75V19a1.75 1.75 0 0 1 1.75-1.75M18.5 2.75h2V21.5h-2");
}

</style>
