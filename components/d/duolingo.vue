<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="ifpde6rvz"/><path class="apq43ebis"/><rect class="k8_r5abhd"/><path class="ppx3lz96f"/><path class="uea1ygbae"/><path class="yca0x3l2q"/><path class="yo3_ulxik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:duolingo" /></template>
<style>
.apq43ebis {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.06 22.11a2.5 2.5 0 0 0-.958.188a2.124 2.124 0 0 1-1.59 3.166v2.288a2.547 2.547 0 0 0 5.095 0v-3.094a2.547 2.547 0 0 0-2.547-2.548");
}

.ifpde6rvz {
  width: 11.188px;
  height: 14.476px;
  x: 6.999px;
  y: 18.918px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.594px;
}

.k8_r5abhd {
  width: 11.188px;
  height: 14.476px;
  x: 29.813px;
  y: 18.918px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.594px;
}

.ppx3lz96f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.865 22.11a2.5 2.5 0 0 0-.959.188a2.124 2.124 0 0 1-1.588 3.166v2.288a2.547 2.547 0 1 0 5.094 0v-3.094a2.547 2.547 0 0 0-2.547-2.548");
}

.uea1ygbae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.077 33.256a8.82 8.82 0 0 0 7.595 4.324h0a8.83 8.83 0 0 0 8.828-8.828v-5.19a8.8 8.8 0 0 0-2.21-5.844h0c0-1.926-.468-4.617-1.771-4.617s-2.509 1.945-2.509 1.945s.815-4.626-1.524-4.626c-3.327 0-5.084 8.956-12.485 8.956s-9.16-8.956-12.486-8.956c-2.34 0-1.525 4.626-1.525 4.626s-1.205-1.945-2.509-1.945s-1.77 2.691-1.77 4.617h0A8.8 8.8 0 0 0 3.5 23.562v5.19a8.83 8.83 0 0 0 8.828 8.828h0a8.82 8.82 0 0 0 7.595-4.324");
}

.yca0x3l2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 33.833l4.9-.694a4.504 4.504 0 0 0-4.9-4.222a4.504 4.504 0 0 0-4.9 4.222Z");
}

.yo3_ulxik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.578 33.326a3.582 3.582 0 1 1-7.156 0");
}

</style>
