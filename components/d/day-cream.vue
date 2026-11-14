<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4br8759y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:day-cream" /></template>
<style>
.u4br8759y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.5h18.5v4H2.75ZM4 7.5V14q0 .123.012.245t.036.243q.024.12.06.238t.082.231t.105.221t.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126q.108.058.221.105q.114.047.231.082t.238.06t.243.036t.245.012h3.973M20 10.454V7.5m-4 10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm1.5-4.25v1m0 6.5v1m-4.25-4.25h1m6.5 0h1m-2-2.25l.75-.75m-.75 5.25l.75.75m-5.25-.75l-.75.75m.75-5.25l-.75-.75");
}

</style>
