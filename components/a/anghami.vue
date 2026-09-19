<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="beii8ie8k"/><path class="p80wqkb0c"/><path class="yxa1fobiv"/><path class="aotue3-ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anghami" /></template>
<style>
.aotue3-ye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.266 29.451a10.75 10.75 0 0 1-9.266 5.3c-5.937 0-10.75-4.813-10.75-10.75S18.063 13.25 24 13.25S34.75 18.064 34.75 24v16.476");
}

.beii8ie8k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.397 42.23A21.5 21.5 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24v19.5");
}

.p80wqkb0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.262 39.337A17.9 17.9 0 0 1 24 41.917c-9.895 0-17.917-8.022-17.917-17.917S14.105 6.083 24 6.083S41.917 14.105 41.917 24v18.492");
}

.yxa1fobiv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.261 34.94a14.33 14.33 0 0 1-9.26 3.394c-7.917 0-14.334-6.418-14.334-14.333S16.085 9.668 24 9.668S38.333 16.085 38.333 24v17.484");
}

</style>
