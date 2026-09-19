<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="l7zm-mb4v"/><path class="oq3m08bls"/><path class="bx2-tmxzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kingdom" /></template>
<style>
.bx2-tmxzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.595 8.566v9.927c-2.474.324-4.689.841-6.532 1.456v-8.7m27.874.001v8.699c-1.843-.615-4.058-1.132-6.532-1.455V8.566");
}

.l7zm-mb4v {
  cx: 24px;
  cy: 33.553px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 19.5px;
  ry: 6.528px;
}

.oq3m08bls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.937 11.25c3.444 1.568 5.562 2.975 5.562 5.336v16.96M10.063 11.25c-3.444 1.568-5.562 2.975-5.562 5.336v16.96m12.094-24.98c2.28-.42 4.786-.646 7.405-.646s5.125.226 7.405.646M6.83 30.458c3.298 2.037 9.749 3.428 17.17 3.428s13.872-1.39 17.17-3.428");
}

</style>
