<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxyrt-h5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-gripper" /></template>
<style>
.yxyrt-h5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-1 6za1.75 1.75 0 0 1 1.275 2.121l-1.573 6.307a1.75 1.75 0 0 1-2.121 1.275a1.75 1.75 0 0 1-1.275-2.121l1.573-6.307A1.75 1.75 0 0 1 8.5 11m7 0za1.75 1.75 0 0 1 2.121 1.275l1.573 6.307a1.75 1.75 0 0 1-1.275 2.121a1.75 1.75 0 0 1-2.121-1.275l-1.573-6.307A1.75 1.75 0 0 1 15.5 11m-4.75-3.75L8.5 11m4.75-3.75L15.5 11");
}

</style>
