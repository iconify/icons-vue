<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w8db5rbbz"/><path class="f8ic3l7pv"/><path class="wxgt_ziwj"/><path class="ufvoybfwa"/><path class="sany0gk-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gitfox" /></template>
<style>
.f8ic3l7pv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 11.267c11.651 0 18.081 6 18.081 6v8.303C42.081 35.547 27 40.22 24 43.5c-3-3.28-18.081-7.953-18.081-17.93v-8.303s6.43-6 18.081-6");
}

.sany0gk-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.66 33.305c-.262-2.197.933-7.494 5.712-9.45c.358 2.36-.841 6.816-5.712 9.45");
}

.ufvoybfwa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.655 12.184c.748-2.293 3.02-7.684 10.426-7.684v12.767C29.465 25.36 27.35 33.872 27.35 41.148a24.4 24.4 0 0 0-6.698 0c0-7.276-2.116-15.787-14.732-23.88V4.5c7.407 0 9.678 5.391 10.426 7.684");
}

.w8db5rbbz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.628 14.764v-5.45a6.74 6.74 0 0 1 3.256 3.957m2.456 20.034c.262-2.197-.933-7.494-5.712-9.45c-.358 2.36.841 6.816 5.712 9.45");
}

.wxgt_ziwj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.372 14.764v-5.45a6.74 6.74 0 0 0-3.256 3.957");
}

</style>
