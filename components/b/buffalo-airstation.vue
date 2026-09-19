<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vlpi2bc9y"/><path class="ff4308b_f"/><path class="rn_dc8bjn"/><path class="dluefvqui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:buffalo-airstation" /></template>
<style>
.dluefvqui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.5 42.5a8 8 0 0 1 8-8m-4 8a4 4 0 0 1 4-4");
}

.ff4308b_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.5 42.5c0-8.837 7.163-16 16-16");
}

.rn_dc8bjn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.5 42.5c0-6.627 5.373-12 12-12");
}

.vlpi2bc9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5C13.783 5.5 5.5 13.783 5.5 24a18.5 18.5 0 0 0 13 17.643v-12.58H11l19.5-17.062L42.43 22.44C41.62 12.864 33.61 5.503 24 5.501z");
}

</style>
