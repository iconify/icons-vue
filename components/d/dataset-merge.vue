<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lmbo0oiji"/><path class="h10054k5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dataset-merge" /></template>
<style>
.h10054k5z {
  d: path("M3 9v9q0 .123.012.245t.036.243t.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126q.108.058.221.105q.114.047.231.082t.238.06t.243.036t.245.012h6.173M21 13.554V9M3 14.75h8.5M10 9v11.5m4.5-5.5c2 0 2 3 4 3m-4 3c2 0 2-3 4-3m0 0h3m-1.75-1.75L21.5 18l-1.75 1.75");
}

.lmbo0oiji {
  fill: currentColor;
  d: path("M3 9V6a2.5 2.5 0 0 1 2.5-2.5h13A2.5 2.5 0 0 1 21 6v3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
