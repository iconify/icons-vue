<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ibn36wypi"/><path class="zxqxcsbhx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:find-vehicle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ibn36wypi {
  d: path("M2.25 11.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m17.255-1.136q-.082-.179-.188-.345t-.235-.316q-.129-.149-.278-.278q-.148-.13-.314-.236q-.166-.107-.345-.189t-.368-.138q-.19-.056-.385-.084T17 8.75q-.135 0-.27.013q-.134.013-.266.04q-.133.026-.262.065q-.13.04-.254.091q-.125.052-.244.116q-.119.063-.232.138q-.112.076-.217.161q-.104.086-.2.181q-.095.096-.181.2t-.161.217t-.138.232q-.064.119-.116.244q-.051.124-.091.254q-.039.129-.065.262q-.027.132-.04.266q-.013.135-.013.27q0 .094.006.187");
}

.zxqxcsbhx {
  d: path("m5 11.5l3.5-5h6l-4.5 5Zm11.463-1.073L14.5 6.5L14 4h2.5m-8 2.5L8 4M6.5 4h3m8.75 17.75c-2.25-2.5-3.25-4-3.25-5.5a3.25 3.25 0 0 1 6.5 0c0 1.5-1 3-3.25 5.5m0-5.5h.01");
}

</style>
