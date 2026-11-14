<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6bzxipuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:curry-paste" /></template>
<style>
.e6bzxipuw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 2.5h7.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 13.75 6h-7.5A1.75 1.75 0 0 1 4.5 4.25A1.75 1.75 0 0 1 6.25 2.5M5.5 6v1.5C3.75 8 3 9 3 11v8q0 .123.012.245t.036.243t.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126q.108.058.221.105q.114.047.231.082t.238.06t.243.036t.245.012h4.94M17 12.287V11c0-2-.75-3-2.5-3.5V6M3 11.5h14M3 17h7.9m3.6 4.25c4.25 0 6.75-2.5 6.5-6.25h-3.5q-.375 3-3 3a1.625 1.625 0 0 0 0 3.25M19.25 15l1-1.75");
}

</style>
