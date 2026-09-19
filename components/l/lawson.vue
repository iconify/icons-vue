<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v6wo-1frk"/><path class="wyoxw_bzp"/><path class="i-t8k4b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lawson" /></template>
<style>
.i-t8k4b_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.003 18.18l2.521-5.725v.008c-1.523-.543-3.431-.857-5.521-.857s-3.999.314-5.521.857v-.008l2.52 5.724");
}

.v6wo-1frk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.303 24L42.5 9.332C38.31 7.157 31.588 5.754 24 5.754S9.69 7.157 5.5 9.332L10.697 24L5.5 38.668c4.19 2.175 10.912 3.578 18.5 3.578s14.31-1.403 18.5-3.578z");
}

.wyoxw_bzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.035 17.8h1.93a5.64 5.64 0 0 1 5.64 5.64v10.82a2.135 2.135 0 0 1-2.134 2.135h-8.942a2.135 2.135 0 0 1-2.134-2.134V23.439a5.64 5.64 0 0 1 5.64-5.639m3.962 0h-5.994l.411-2.015l-.411-2.015h5.994l-.411 2.015z");
}

</style>
