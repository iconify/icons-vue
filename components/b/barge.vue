<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lffypfblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:barge" /></template>
<style>
.lffypfblq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.94 11.39l1.62-2.28Q8 8.5 8.75 8.5h6.5q.75 0 1.19.61l1.62 2.28q.44.61-.31.61H6.25q-.75 0-.31-.61M3.75 12h16.5q1 0 .68.95l-.36 1.1q-.32.95-1.32.95H4.75q-1 0-1.32-.95l-.36-1.1q-.32-.95.68-.95m-.5 7c1.5 0 1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1");
}

</style>
