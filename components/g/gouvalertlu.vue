<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="yfzpeb1mc"/><path class="lj9dr1cce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gouvalertlu" /></template>
<style>
.lj9dr1cce {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.305 4.5h-4.779l-3.25 28.629h4.779z");
}

.yfzpeb1mc {
  cx: 22.805px;
  cy: 39.39px;
  r: 4.11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
