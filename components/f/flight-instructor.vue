<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew6hq4btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flight-instructor" /></template>
<style>
.ew6hq4btc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8h15m-13 0C5.5 4.5 8 3 11 3s5.5 1.5 5.5 5M7 8v2.5q0 .197.019.392q.02.196.058.388q.038.193.095.381t.132.37t.168.355t.202.336t.234.316q.125.151.264.29t.29.264t.316.234q.163.109.336.202q.174.092.355.168q.182.075.37.132t.381.095t.388.058t.392.019q.323 0 .642-.052m1.707-.71q.191-.139.364-.299q.174-.16.327-.34q.154-.179.285-.375t.238-.407t.189-.432t.137-.451q.055-.229.083-.463T15 10.5V8M3.5 21.5c0-2.463 3.155-4.198 7.312-4.249M13.5 16.5l2.5 3h3.5l2.5-3");
}

</style>
