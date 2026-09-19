<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cwbab8n4g"/><path class="v-tmesbcv"/><circle class="oh080lb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:best-before" /></template>
<style>
.cwbab8n4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.4 19.8h-7.9l-7.8-13c-.5-1-1.8-1.3-2.7-.8c-.3.2-.6.5-.8.8l-7.8 13H6.6c-1.7 0-3.1 1.4-3.1 3.1c0 .3 0 .5.1.8L8 40.1c.3 1.2 1.5 2.1 2.7 2.1h26.5c1.3 0 2.4-.9 2.8-2.1l4.4-16.3c.4-1.7-.5-3.4-2.2-3.8c-.3-.1-.5-.2-.8-.2");
}

.oh080lb6g {
  cx: 24px;
  cy: 31px;
  r: 4.8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v-tmesbcv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 11.8l4.8 8h-9.6z");
}

</style>
