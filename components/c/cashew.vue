<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l520j0b3t"/><path class="c2s_d3r3u"/><path class="ur15wabak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cashew" /></template>
<style>
.c2s_d3r3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.876 0 21.5 9.624 21.5 21.5S35.876 45.5 24 45.5S2.5 35.876 2.5 24S12.124 2.5 24 2.5M34 24h11.5m-14.454-7.046l8.156-8.156");
}

.l520j0b3t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 14c5.524 0 10 4.476 10 10s-4.476 10-10 10s-10-4.476-10-10s4.476-10 10-10");
}

.ur15wabak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.033 34c3.045 0 5.514 2.574 5.514 5.75s-2.469 5.75-5.514 5.75M2.5 24c0-3.045 2.574-5.514 5.75-5.514S14 20.955 14 24m7.01 3.748c.589.766 1.327 1.052 2.354 1.052h1.421a2.397 2.397 0 0 0 2.395-2.4h0c0-1.325-1.072-2.4-2.395-2.4h-1.57a2.397 2.397 0 0 1-2.395-2.4h0c0-1.325 1.072-2.4 2.395-2.4h1.421c1.027 0 1.765.286 2.354 1.052M24 19.2V18m0 12v-1.2");
}

</style>
