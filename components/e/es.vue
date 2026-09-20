<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qieekrxlc"/><path class="y4ox6nbdu"/><path class="yq6-2ub5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:es" /></template>
<style>
.qieekrxlc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.68 13H24.77c-2-.1-5.93-4.23-8.19-4.23h-9.9A2.18 2.18 0 0 0 4.5 11v7.29h39v-3.42A1.83 1.83 0 0 0 41.68 13");
}

.y4ox6nbdu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 18.28h-39V37a2.18 2.18 0 0 0 2.17 2.2h34.65A2.18 2.18 0 0 0 43.5 37ZM25.32 33.82h5.1m-5.1-10.2h5.1m-5.1 5.1h3.33m-3.33-5.1v10.2");
}

.yq6-2ub5c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.58 32.7a2.85 2.85 0 0 0 2.5 1.12h1.51a2.55 2.55 0 0 0 2.54-2.55a2.55 2.55 0 0 0-2.54-2.55h-1.67a2.55 2.55 0 0 1-2.55-2.55a2.55 2.55 0 0 1 2.55-2.55h1.51a2.86 2.86 0 0 1 2.5 1.11");
}

</style>
