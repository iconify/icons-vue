<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="iv34yub_k"/><path class="yazjg8bzf"/><path class="xtjozdb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:instagram-downloader" /></template>
<style>
.iv34yub_k {
  cx: 38.5px;
  cy: 38.499px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xtjozdb5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.203 39.203l3.297 3.296l3.297-3.296M35.38 10.46a2.19 2.19 0 1 0 2.16 2.22v-.06a2.18 2.18 0 0 0-2.16-2.16M24 15.72A8.28 8.28 0 1 0 32.28 24h0A8.28 8.28 0 0 0 24 15.72");
}

.yazjg8bzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.432 43.326A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24c0 3.383-.781 6.583-2.173 9.43M38.5 42.499v-8");
}

</style>
