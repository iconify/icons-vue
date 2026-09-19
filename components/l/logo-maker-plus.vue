<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="rvnxq1bkd"/><path class="k6bnw650l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:logo-maker-plus" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k6bnw650l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.772 39.36a1.31 1.31 0 0 1-1.312-1.312V16.02c0-3.12-2.53-5.66-5.66-5.66h-.29v22.028c0 .725.587 1.312 1.312 1.312H26.66c3.13 0 5.66 2.54 5.66 5.66z");
}

.rvnxq1bkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.93 22.66v-1.256a2.665 2.665 0 0 0-2.664-2.665h-.388v3.92h-1.256a2.665 2.665 0 0 0-2.665 2.665v.389h3.92v1.255a2.665 2.665 0 0 0 2.666 2.665h.388v-3.92h1.255a2.665 2.665 0 0 0 2.665-2.665v-.388z");
}

</style>
