<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lmbo0oiji"/><path class="txhsk3bis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dataset-check" /></template>
<style>
.lmbo0oiji {
  fill: currentColor;
  d: path("M3 9V6a2.5 2.5 0 0 1 2.5-2.5h13A2.5 2.5 0 0 1 21 6v3Z");
}

.txhsk3bis {
  d: path("M3 9v9q0 .123.012.245t.036.243t.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126q.108.058.221.105q.114.047.231.082t.238.06t.243.036t.245.012h7.573M21 11.854V9M3 14.75h10.8m1.4 0h3.2M10 9v11.5m4.5-2.5l2.5 2.5l4.5-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
