<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k0mxzgeun"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crowdfunding" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k0mxzgeun {
  d: path("M2.75 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.25 7.5a2.25 2.25 0 0 1 4.5 0M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.25 7.5a2.25 2.25 0 0 1 4.5 0m3-7.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.229 7.193q.014-.1.037-.198t.054-.194t.071-.189t.088-.181t.104-.173t.118-.163t.133-.151q.07-.073.146-.139t.158-.125q.081-.06.168-.111t.178-.096q.091-.043.185-.079q.094-.035.192-.062q.097-.026.196-.044t.2-.027t.201-.009q.11 0 .22.01t.219.033q.108.021.214.053t.208.075t.199.094t.19.113q.091.062.177.132t.163.148q.079.078.149.163t.131.178q.062.092.114.189t.094.199t.075.208t.054.214t.032.219t.011.22M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

</style>
