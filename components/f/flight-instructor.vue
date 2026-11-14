<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czgrckbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flight-instructor" /></template>
<style>
.czgrckbzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8h15m-13 0C5.5 4.5 8 3 11 3s5.5 1.5 5.5 5M7 8v2.5q0 .197.019.392q.02.196.058.388q.038.193.095.381t.132.37t.168.355t.202.336t.234.316q.125.151.264.29t.29.264t.316.234q.163.109.336.202q.174.092.355.168q.182.075.37.132t.381.095t.388.058t.392.019q.323 0 .642-.052m2.552-1.54q.195-.258.345-.545q.151-.286.254-.593t.155-.627T15 10.5V8M3.5 21.5c0-2.395 2.982-4.101 6.968-4.241M13.5 16.5l2.5 3h3.5l2.5-3");
}

</style>
