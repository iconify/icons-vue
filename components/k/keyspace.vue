<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="erechcchl"/><path class="gzez0s0wn"/><path class="c65uduupz"/><path class="uh6zb60av"/><path class="x56db-bwc"/><path class="x1d5pxbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keyspace" /></template>
<style>
.c65uduupz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.239 20.102l3.952 1.771l-18.328 8.78l-18.054-8.601l3.893-1.95");
}

.erechcchl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.021 5L5.81 13.893l18.054 7.98l18.328-7.98z");
}

.gzez0s0wn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.81 13.893v4.342l18.053 8.66l18.328-8.66v-4.342m-18.328 7.98v5.021");
}

.uh6zb60av {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.19 21.873v4.458L23.864 34.96L5.809 26.331v-4.28m18.054 8.601v4.307");
}

.x1d5pxbnp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.19 29.921v4.36L23.864 43L5.809 34.179v-4.232m18.054 8.846V43");
}

.x56db-bwc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.284 28.187l3.907 1.734l-18.328 8.872l-18.028-8.846l3.857-1.76");
}

</style>
