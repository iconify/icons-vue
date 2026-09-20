<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m4sqo-nti"/><circle class="edi79mb8h"/><circle class="cpk0fnbgt"/><circle class="cps8tpbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gravitybox" /></template>
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

.cps8tpbrh {
  cx: 24px;
  cy: 24px;
  r: 16.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.edi79mb8h {
  cx: 24px;
  cy: 24px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m4sqo-nti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.814 15.186c-2.044 2.814-1.017 4.23 2.293 3.155a12.5 12.5 0 0 1 1.205 3.709c-3.308 1.075-3.31 2.825 0 3.9a12.5 12.5 0 0 1-1.205 3.71c-3.309-1.076-4.338.339-2.293 3.154a12.5 12.5 0 0 1-3.155 2.293c-2.044-2.815-3.709-2.275-3.709 1.205a12.5 12.5 0 0 1-3.9 0c0-3.479-1.664-4.02-3.71-1.205a12.5 12.5 0 0 1-3.154-2.293c2.044-2.814 1.017-4.23-2.293-3.155a12.5 12.5 0 0 1-1.205-3.709c3.308-1.075 3.31-2.825 0-3.9a12.5 12.5 0 0 1 1.205-3.71c3.309 1.076 4.338-.339 2.293-3.154a12.5 12.5 0 0 1 3.155-2.293c2.045 2.814 3.709 2.275 3.709-1.205a12.5 12.5 0 0 1 3.9 0c0 3.479 1.664 4.02 3.71 1.205a12.5 12.5 0 0 1 3.154 2.293");
}

</style>
