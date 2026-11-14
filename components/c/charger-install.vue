<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wv9sgcc5d"/><path class="a0yc6obot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charger-install" /></template>
<style>
.a0yc6obot {
  d: path("M10 5.5L7 10h2.5l-1 3L12 8.5H9.5Zm9.5 9a2.25 2.25 0 1 0 2 2m-3.75 1.75L15 21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wv9sgcc5d {
  d: path("M14.3 16H3.5V2.5h11v12.6M7 16v2.5q0 .123.012.245t.036.243t.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126t.221.105q.114.047.231.082t.238.06t.243.036T9.5 21h1.573");
}

</style>
