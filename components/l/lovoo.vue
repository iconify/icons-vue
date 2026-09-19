<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="twhp69b-x"/><path class="t6pezsbvy"/><path class="kr0v6gb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lovoo" /></template>
<style>
.kr0v6gb7p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 5.5A12.333 12.333 0 0 1 42.5 17.833v12.334h0h-12.333a12.333 12.333 0 0 1-12.334-12.334v0A12.333 12.333 0 0 1 30.167 5.5");
}

.t6pezsbvy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 42.5H17.833A12.333 12.333 0 0 1 5.5 30.167h0a12.333 12.333 0 0 1 12.333-12.334h0a12.333 12.333 0 0 1 12.334 12.334");
}

.twhp69b-x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 19.483a12.3 12.3 0 0 1 6.167-1.65h0A12.333 12.333 0 0 1 42.5 30.167V42.5H30.167a12.333 12.333 0 0 1-12.334-12.333h0a12.3 12.3 0 0 1 1.652-6.17");
}

</style>
