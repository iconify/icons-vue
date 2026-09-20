<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jshjagbts"/><path class="tj0isxbip"/><path class="bdyu_cgfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lovoo" /></template>
<style>
.bdyu_cgfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 5.5zA12.333 12.333 0 0 1 42.5 17.833v12.334H30.167a12.333 12.333 0 0 1-12.334-12.334A12.333 12.333 0 0 1 30.167 5.5");
}

.jshjagbts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 19.483a12.3 12.3 0 0 1 6.167-1.65A12.333 12.333 0 0 1 42.5 30.167V42.5H30.167a12.333 12.333 0 0 1-12.334-12.333a12.3 12.3 0 0 1 1.652-6.17");
}

.tj0isxbip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 42.5H17.833A12.333 12.333 0 0 1 5.5 30.167a12.333 12.333 0 0 1 12.333-12.334a12.333 12.333 0 0 1 12.334 12.334");
}

</style>
