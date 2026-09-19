<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jhzsk7f9z"/><path class="xg7tmwbrq"/><circle class="h2_sejbcu"/><circle class="kdb-h87xp"/><circle class="c1ru8rb7r"/><circle class="iufjqt7sp"/><path class="vw-6frtra"/><path class="hr2t0bc1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:frogweather" /></template>
<style>
.c1ru8rb7r {
  cx: 25.289px;
  cy: 33.223px;
  r: 0.75px;
  fill: currentColor;
}

.h2_sejbcu {
  cx: 13.089px;
  cy: 25.883px;
  r: 0.75px;
  fill: currentColor;
}

.hr2t0bc1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.66 16.56c-2.678-.992-5.158-.992-7.538 0C10.907 8.13 16.76 5.154 24 3.864c7.24 1.19 13.093 4.166 14.878 12.696c-2.48-.992-4.86-.992-7.538 0");
}

.iufjqt7sp {
  cx: 22.711px;
  cy: 33.223px;
  r: 0.75px;
  fill: currentColor;
}

.jhzsk7f9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.355 26.28c3.967-1.388 9.323-1.388 13.29 0m5.952 3.57c1.289 1.39 1.983 3.076 1.983 4.861c0 14.68-38.385 10.712-27.177-4.86");
}

.kdb-h87xp {
  cx: 34.91px;
  cy: 25.883px;
  r: 0.75px;
  fill: currentColor;
}

.vw-6frtra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.015 37.587c9.323 2.778 18.548 2.778 27.871 0M24 22.908v-5.753m-7.34-.595c1.091-5.654 3.57-9.92 7.34-12.696c3.77 2.777 6.249 6.943 7.34 12.696c-4.86-1.389-9.82-1.389-14.68 0");
}

.xg7tmwbrq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.355 25.883c.099 5.555-8.63 5.555-8.53 0c-.1-5.554 8.629-5.554 8.53 0m21.821 0c.099 5.555-8.63 5.555-8.53 0c-.1-5.554 8.629-5.554 8.53 0");
}

</style>
