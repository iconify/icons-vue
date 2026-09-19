<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="guwqcv-1c"/><path class="txlt7w7gv"/><path class="yl3rfiucl"/><path class="oe147uaim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drik-panchang" /></template>
<style>
.guwqcv-1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.91 5.5c2.3 0 4.163 2.074 4.163 4.627s-1.862 4.619-4.163 4.619c-2.294 0-4.156-2.066-4.156-4.619S16.616 5.5 18.91 5.5m-5.66 9.962h7.627a1.27 1.27 0 0 1 1.277 1.26V27a1.27 1.27 0 0 1-1.268 1.27H13.25a1.27 1.27 0 0 1-1.277-1.261V16.73c0-.702.568-1.27 1.269-1.27z");
}

.oe147uaim {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 36.808l9.254 5.692L42.5 38.938M22 16.137c4.155 4.797 4.155 13.198 9.872 14.393");
}

.txlt7w7gv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.973 16.169c-9.246 8.539-1.846 16.37 1.854 16.37");
}

.yl3rfiucl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.746 38.938l25.9-3.553l-8.726-4.969l-24.566 2.83z");
}

</style>
