<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v-ucd_b1s"/><path class="p7deq4r8h"/><circle class="mxyg-_bsp"/><path class="gc9uz-bmn"/><circle class="ljd6h0wlw"/><path class="nevlyntbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adb-otg" /></template>
<style>
.gc9uz-bmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 36.345c0-.202.1-.403.302-.504l3.024-1.713c.403-.302.705-.605.705-1.008v-1.31M24 36.95v-9.07m1.713-.202L24 24.756l-1.713 3.023z");
}

.ljd6h0wlw {
  cx: 19.767px;
  cy: 31.004px;
  r: 1.209px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mxyg-_bsp {
  cx: 24px;
  cy: 38.864px;
  r: 1.713px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nevlyntbg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.767 32.314v1.713c0 .302.303.504.706.706l3.124 1.31c.201.1.403.201.403.403m5.341-7.659v2.418h-2.419v-2.418z");
}

.p7deq4r8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 6.415zc7.558 0 13.705 6.147 13.705 13.705a1.913 1.913 0 0 1-1.914 1.915H12.209a1.913 1.913 0 0 1-1.914-1.915A13.655 13.655 0 0 1 24 6.415M11.705 4.5l4.233 4.233M36.295 4.5l-4.334 4.333");
}

.v-ucd_b1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.543 14.275c1.007 0 1.914.907 1.914 1.915s-.907 1.915-1.914 1.915s-1.915-.907-1.915-1.915s.907-1.915 1.915-1.915m-11.086 0c1.008 0 1.915.907 1.915 1.915s-.907 1.915-1.915 1.915s-1.914-.907-1.914-1.915s.806-1.915 1.914-1.915m17.333 7.76H12.21a1.913 1.913 0 0 0-1.915 1.915v5.945C10.295 37.453 16.442 43.5 24 43.5s13.705-6.147 13.705-13.605V23.85c0-1.008-.907-1.814-1.914-1.814Z");
}

</style>
