<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bdilonbnn"/><circle class="mrd8l1eft"/><circle class="q5udh4w6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adobescan" /></template>
<style>
.bdilonbnn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.5 5.5h-33a2 2 0 0 0-2 2v33a2 2 0 0 0 2 2h33a2 2 0 0 0 2-2v-33a2 2 0 0 0-2-2Zm-1.89 26.43l-3.6.7v4.31L24 34.79l-11 2.15v-4.31l-3.6-.7V16.07l3.6-.7v-4.31l11 2.15l11-2.15v4.31l3.6.7ZM24 13.21l11.01 2.16m-22.02 0v17.26M24 34.79l11.01-2.16");
}

.mrd8l1eft {
  cx: 24px;
  cy: 24px;
  r: 7.71px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q5udh4w6y {
  cx: 24px;
  cy: 24px;
  r: 5.07px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
