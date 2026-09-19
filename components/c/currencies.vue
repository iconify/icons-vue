<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bvrc5msow"/><path class="zhkk94b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:currencies" /></template>
<style>
.bvrc5msow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.5 19.125l-13 11.917l13 11.916m13-37.916l13 13l-13 13");
}

.zhkk94b6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.817 33.967a2.58 2.58 0 0 0 2.166.975h1.3a2.167 2.167 0 0 0 0-4.334h-1.408a2.167 2.167 0 1 1 0-4.333h1.3a2.33 2.33 0 0 1 2.167.975m-2.817-2.167v10.834m18.308-14.625a2.88 2.88 0 0 1-2.275 1.083a2.913 2.913 0 0 1-2.925-2.925v-2.817a2.913 2.913 0 0 1 2.925-2.925a3.05 3.05 0 0 1 2.275 1.084m-6.5 2.058h3.684m-3.684 2.167h3.684");
}

</style>
