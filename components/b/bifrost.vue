<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c7pu-tbmt"/><path class="h5vnof11t"/><path class="brir49fua"/><path class="naumxvmpi"/><path class="ivb69iqig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bifrost" /></template>
<style>
.brir49fua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.427 26.135c.354-13.601 11.855-14.127 17.782-12.208");
}

.c7pu-tbmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 26.135l6.806 6.27l6.796-6.27zm0 10.451h13.602m9.411-13.591c-5.231-1.05-5.231-6.796 1.04-7.32c0-5.231 9.42-6.282 9.42 1.039c4.706 0 4.706 6.28-.02 6.28z");
}

.h5vnof11t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.69 26.135c0-13.601 11.148-16.742 20.913-13.601");
}

.ivb69iqig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.91 26.135c0-7.32 5.231-10.46 10.987-9.421");
}

.naumxvmpi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.174 26.135c.172-10.46 8.018-12.551 15.542-10.675");
}

</style>
