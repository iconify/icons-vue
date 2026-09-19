<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v357x7bxn"/><path class="h59-i1blf"/><path class="x5aen68_h"/><path class="dfq50mbql"/><path class="wl3l5zbrq"/><path class="e8xwcebil"/><path class="a1cklxben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:biznesradarpl" /></template>
<style>
.a1cklxben {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24H24v21.5");
}

.dfq50mbql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.732c-5.67 0-10.268 4.597-10.268 10.268S18.329 34.268 24 34.268S34.268 29.671 34.268 24");
}

.e8xwcebil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 21.22A2.78 2.78 0 1 0 26.78 24");
}

.h59-i1blf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 6.244c-9.806 0-17.756 7.95-17.756 17.756S14.194 41.756 24 41.756S41.756 33.806 41.756 24");
}

.v357x7bxn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5C12.126 2.5 2.5 12.126 2.5 24S12.126 45.5 24 45.5S45.5 35.874 45.5 24");
}

.wl3l5zbrq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 17.476A6.524 6.524 0 1 0 30.524 24");
}

.x5aen68_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 9.988C16.261 9.988 9.988 16.261 9.988 24S16.261 38.012 24 38.012S38.012 31.739 38.012 24");
}

</style>
