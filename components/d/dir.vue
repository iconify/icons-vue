<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="hqsq0ub7x"/><path class="kl4st9bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dir" /></template>
<style>
.hqsq0ub7x {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.kl4st9bea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.791 33.099V14.9m5.617 0c5.965 0 10.8 4.074 10.801 9.1h0c0 5.026-4.836 9.1-10.8 9.1h0z");
}

</style>
