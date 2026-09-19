<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ozbsqv_fg"/><path class="rsl2jrb-v"/><path class="j5hjqd7ma"/><path class="jlc0kdt5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adb-over-wifi" /></template>
<style>
.j5hjqd7ma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.522 13.275q6.478-6.327 12.956 0");
}

.jlc0kdt5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.745 11.206q9.255-9.075 18.51 0m-19.969 3.592l2.392 9.009m16.644 0l2.392-9.009m-1.952 15.09a2.434 2.434 0 1 1 .002 4.87a2.434 2.434 0 0 1-.002-4.87");
}

.ozbsqv_fg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 41.331c0-10.756 8.283-19.476 18.5-19.476s18.5 8.72 18.5 19.476z");
}

.rsl2jrb-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.238 29.888c1.34 0 2.435 1.094 2.435 2.434s-1.094 2.435-2.435 2.435c-1.351 0-2.434-1.094-2.434-2.435s1.083-2.434 2.434-2.434M20.3 15.345q3.7-2.928 7.4 0");
}

</style>
