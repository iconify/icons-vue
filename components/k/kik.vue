<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oxanjgb9s"/><circle class="mcp-v6b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kik" /></template>
<style>
.mcp-v6b2m {
  cx: 39.02px;
  cy: 23.97px;
  r: 1.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oxanjgb9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.5 7.59h-35a2 2 0 0 0-2 2v22.5a2 2 0 0 0 2 2h3.16v6.32L16 34.09h25.5a2 2 0 0 0 2-2V9.59a2 2 0 0 0-2-2M8.56 12.4v17m.01-3.62l7.69-7.65m-5.25 5.22l6.05 6.02M27.54 12.4v17m0-3.62l7.69-7.65m-5.24 5.22l6.05 6.02M22.3 18.13V29.4");
}

</style>
