<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xr7275wip"/><circle class="g0r6lmb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:custom-aim" /></template>
<style>
.g0r6lmb8y {
  cx: 24px;
  cy: 24px;
  r: 0.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xr7275wip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.562 7.217a21.5 21.5 0 0 1 26.88.003m7.764 20.323a21.5 21.5 0 0 1-4.423 9.895m4.685-14.618q.032.59.032 1.18t-.032 1.18M40.78 10.558a21.5 21.5 0 0 1 4.426 9.898m-42.412.001a21.5 21.5 0 0 1 4.423-9.895M2.532 25.18a22 22 0 0 1 0-2.36m4.685 14.618a21.5 21.5 0 0 1-4.423-9.895m34.644 13.24a21.5 21.5 0 0 1-26.876 0m26.105-26.098a15.7 15.7 0 0 1 2.834 6.68M26.64 8.5a15.7 15.7 0 0 1 6.675 2.833M11.333 33.315A15.7 15.7 0 0 1 8.5 26.641M21.36 39.5a15.7 15.7 0 0 1-6.675-2.833M31.487 18.87a9.07 9.07 0 0 1 .001 10.257M18.871 16.513a9.08 9.08 0 0 1 10.261.001m-12.62 12.613a9.07 9.07 0 0 1 0-10.254m12.617 12.614a9.08 9.08 0 0 1-10.258 0M28.292 24h6.985m-22.554 0h6.985M24 28.292v6.985m0-22.554v6.985m4.934-.642L44.138 3.862M29.654 24a5.654 5.654 0 1 1-11.308 0a5.654 5.654 0 0 1 11.308 0");
}

</style>
