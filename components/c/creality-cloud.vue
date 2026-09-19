<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tkwnybcaa"/><path class="oxhyv1b4f"/><path class="ybah_dw5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:creality-cloud" /></template>
<style>
.oxhyv1b4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.124 25.688v16.17L5.5 29.327V12.61m37 .002v16.715l-18.376 12.53");
}

.tkwnybcaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.833 6.142l9.291 6.538l8.947-6.538l9.429 6.47l-18.376 13.076L5.5 12.612z");
}

.ybah_dw5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.312 35.592V19.15l-9.188-6.47l-9.312 6.47v16.442");
}

</style>
