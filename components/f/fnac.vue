<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vlr1xybso"/><path class="sgzlxacmv"/><path class="in1dygk4z"/><path class="d1gxu0bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fnac" /></template>
<style>
.d1gxu0bqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.07 16.59c.761-.581 1.295-.632 2.767-.632c1.67 0 2.768.56 2.768 2.07v4.308");
}

.in1dygk4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.653 22.336v-7.942c0-.93.991-1.685 2.214-1.685c1.09 0 1.77.246 2.237.705m14.5 6.516c0 1.33-1.405 2.407-3.139 2.407h-1.102c-1.148 0-2.08-.714-2.08-1.595s.932-1.594 2.08-1.594h4.247");
}

.sgzlxacmv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.396 21.124c-.545.724-1.571 1.212-2.747 1.212c-1.747 0-3.163-1.077-3.163-2.407v-1.564c0-1.33 1.416-2.407 3.163-2.407c1.174 0 2.198.486 2.744 1.208m-15.985 5.17v-3.971c0-1.33-1.416-2.407-3.163-2.407s-3.163 1.077-3.163 2.407m-6.31-2.407h6.31v6.377");
}

.vlr1xybso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.046 5.5L42.5 11.046L36.954 42.5L5.5 36.954z");
}

</style>
