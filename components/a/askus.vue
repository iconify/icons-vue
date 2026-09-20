<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="vrey2nuie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:askus" /></template>
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

.vrey2nuie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.84 2.689a9 9 0 0 1-15.22 8.775m-2.156 3.753a9 9 0 0 1-.002 17.567m2.155 3.748a9 9 0 0 1 15.631 6.086a9 9 0 0 1-.416 2.704M41.43 11.408a9 9 0 0 1-15.244-8.803m17.352 30.178a9 9 0 0 1 .075-17.583m-17.45 30.124a9 9 0 0 1 15.21-8.794");
}

</style>
