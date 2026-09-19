<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n9kgk9_fe"/><path class="owry9q8bg"/><path class="n3c7y8oqc"/><path class="kfy179bdh"/><path class="c7hcoybli"/><path class="i1xh4tq0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:droidupnp" /></template>
<style>
.c7hcoybli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 10.5c17.673 0 32 14.327 32 32");
}

.i1xh4tq0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5c20.435 0 37 16.566 37 37m-27 0h5m6 0h5m6 0h5m-37-37v5m0 6v5m0 6v5");
}

.kfy179bdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 16.5c14.36 0 26 11.64 26 26");
}

.n3c7y8oqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 21.5c11.598 0 21 9.402 21 21");
}

.n9kgk9_fe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 32.5c5.523 0 10 4.477 10 10");
}

.owry9q8bg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 27.5c8.284 0 15 6.716 15 15");
}

</style>
