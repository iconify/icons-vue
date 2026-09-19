<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iox5xvbzs"/><circle class="nl4qj1x6s"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:a8ballpool" /></template>
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

.iox5xvbzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.8 20.65a3.38 3.38 0 0 0 3-3.75h0a3.39 3.39 0 0 0-3.75-3l-2.19.25a3.4 3.4 0 0 0-3 3.76h0a3.4 3.4 0 0 0 3.76 3l2.18-.26l-2.18.26a3.39 3.39 0 0 0-3 3.75h0a3.4 3.4 0 0 0 3.76 3l2.18-.26a3.39 3.39 0 0 0 3-3.75h0a3.4 3.4 0 0 0-3.76-3");
}

.nl4qj1x6s {
  cx: 23.1px;
  cy: 21.53px;
  r: 12.09px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
