<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o6s1wch5a"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:currency-dollar" /></template>
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

.o6s1wch5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.52 30.877c1.08 1.404 2.432 1.928 4.314 1.928h2.605a4.394 4.394 0 0 0 4.389-4.399h0a4.394 4.394 0 0 0-4.39-4.398h-2.877a4.394 4.394 0 0 1-4.39-4.399h0a4.394 4.394 0 0 1 4.39-4.398h2.605c1.882 0 3.235.523 4.313 1.927M24 34.996V13.004");
}

</style>
