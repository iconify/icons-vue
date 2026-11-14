<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou0ditbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-sterile" /></template>
<style>
.ou0ditbzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3H19M5 3v15.5q0 .123.012.245t.036.243t.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126q.108.058.221.105q.114.047.231.082t.238.06t.243.036T7.5 21h6.973m3.027-6.746V3M5 9.5h5m8.5 5.25Q19 18 22 18.5q-3 .5-3.5 3.5q-.5-3-3.5-3.5q3-.5 3.5-3.75Z");
}

</style>
