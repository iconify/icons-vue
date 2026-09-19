<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ef-wulbpu"/><circle class="ztz6rwnfn"/><circle class="z5ltyhp7b"/><circle class="f857xmbiu"/><circle class="x0118fbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:funmax" /></template>
<style>
.ef-wulbpu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.25 22.611v-5.427m-2.713 2.713h5.426m12.081 6.755l4.553 6.83a5.405 5.405 0 0 0 9.786-4.108c-.984-4.67-1.769-9.026-2.572-11.982c-.846-3.113-3.884-5.28-7.284-5.28c-2.052 0-3.912.81-5.288 2.123h-8.478a7.64 7.64 0 0 0-5.287-2.124c-3.401 0-6.44 2.168-7.285 5.28c-.803 2.957-1.588 7.313-2.572 11.983a5.405 5.405 0 0 0 9.787 4.107l4.553-6.83z");
}

.f857xmbiu {
  cx: 33.75px;
  cy: 17.184px;
  r: 0.75px;
  fill: currentColor;
}

.x0118fbod {
  cx: 33.75px;
  cy: 22.611px;
  r: 0.785px;
  fill: currentColor;
}

.z5ltyhp7b {
  cx: 36.463px;
  cy: 19.897px;
  r: 0.75px;
  fill: currentColor;
}

.ztz6rwnfn {
  cx: 31.03px;
  cy: 19.897px;
  r: 0.75px;
  fill: currentColor;
}

</style>
