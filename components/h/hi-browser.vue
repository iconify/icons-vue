<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="u2i1tacww"/><path class="q8k544bxc"/><path class="w-8qusfjn"/><path class="n29ziz9rf"/><path class="o703jpbrf"/><path class="sfneprbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hi-browser" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n29ziz9rf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.08 6.813c6.704-5.04 16.224-3.69 21.264 3.014s3.69 16.224-3.014 21.264");
}

.o703jpbrf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.353 6.401c6.865 4.819 8.524 14.29 3.705 21.155s-14.29 8.523-21.154 3.705");
}

.q8k544bxc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.35 45.497c-8.386.137-15.295-6.55-15.431-14.937c-.137-8.386 6.55-15.295 14.937-15.431");
}

.sfneprbgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.559 30.312c-2.462 8.017-10.957 12.522-18.974 10.06c-8.018-2.461-12.523-10.957-10.061-18.974");
}

.u2i1tacww {
  cx: 24px;
  cy: 24px;
  r: 8.872px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w-8qusfjn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.658 30.978c-2.722-7.933 1.504-16.57 9.437-19.292c7.933-2.721 16.57 1.504 19.292 9.437");
}

</style>
