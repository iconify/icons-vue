<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="mem18ybbx"/><path class="znmpg9a4n"/><circle class="e_mgrzy9n"/><path class="diytnrbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amazonmusic" /></template>
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

.diytnrbrn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.88 20.125v5.3m-5.34-.452a2.25 2.25 0 0 0 1.646.447h.448a1.324 1.324 0 0 0 1.322-1.325h0a1.324 1.324 0 0 0-1.322-1.325h-.897a1.324 1.324 0 0 1-1.322-1.325h0a1.324 1.324 0 0 1 1.322-1.325h.449a2.25 2.25 0 0 1 1.644.448m7.77 3.85a2 2 0 0 1-1.737 1.007h0a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2h0a2 2 0 0 1 1.735 1.004");
}

.e_mgrzy9n {
  cx: 31.88px;
  cy: 17.675px;
  r: 0.7px;
  fill: currentColor;
}

.mem18ybbx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.28 29.7c1.113-.45 3.092-1.048 3.688-.326c.644.781-.17 2.477-.92 3.794");
}

.znmpg9a4n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.798 30.223c1.759 1.397 6.954 3.535 12.488 3.535a17 17 0 0 0 10.167-3.08M20.404 20.125v3.3a2 2 0 0 0 2 2h0a2 2 0 0 0 2-2v-3.3m0 3.3v2m-14.004-3.2a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v3.2m-4-5.2v5.2m4-3.2a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v3.2");
}

</style>
