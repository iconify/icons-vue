<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr_vipbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:humidifier" /></template>
<style>
.lr_vipbut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 9.5h2a3.5 3.5 0 0 1 3.5 3.5v1.5A3.5 3.5 0 0 1 13 18h-2a3.5 3.5 0 0 1-3.5-3.5V13A3.5 3.5 0 0 1 11 9.5M7.25 18h9.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-9.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 7.25 18M9 6.75C8 5.5 10 4 9 2.5m3 4.25C11 5.5 13 4 12 2.5m3 4.25C14 5.5 16 4 15 2.5");
}

</style>
