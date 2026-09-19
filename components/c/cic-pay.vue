<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="urd-uxb4w"/><path class="ftoh3nb_g"/><path class="k3n6shbew"/><path class="x8j5ygnpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cic-pay" /></template>
<style>
.ftoh3nb_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.833 9.051v13.542h4.334");
}

.k3n6shbew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.833 12.843h4.334v13.541m-8.992-4.766a4.875 4.875 0 1 1 0-7.8m21.667 0a4.875 4.875 0 1 0 0 7.8m-5.391 11.747v3.208a2.376 2.376 0 0 1-2.376 2.376h0c-.656 0-1.25-.266-1.68-.696");
}

.urd-uxb4w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 9.051h39v17.333h-39z");
}

.x8j5ygnpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.451 29.445v3.92a2.376 2.376 0 0 1-2.376 2.376h0a2.376 2.376 0 0 1-2.376-2.376v-3.92m-2.382 3.92a2.376 2.376 0 0 1-2.376 2.376h0a2.376 2.376 0 0 1-2.376-2.376v-1.544a2.376 2.376 0 0 1 2.376-2.376h0a2.376 2.376 0 0 1 2.376 2.376m0 3.92v-6.296m-11.768 3.92a2.376 2.376 0 0 0 2.376 2.376h0a2.376 2.376 0 0 0 2.376-2.376v-1.544a2.376 2.376 0 0 0-2.376-2.376h0a2.376 2.376 0 0 0-2.376 2.376m0-2.376v9.504");
}

</style>
