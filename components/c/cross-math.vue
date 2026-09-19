<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ayashnh_b"/><path class="vmwnxib_i"/><circle class="vmmqegbrt"/><circle class="aylyldbyl"/><path class="wu3zbts9r"/><circle class="wse7k0x-m"/><path class="d-889th1y"/><circle class="xsqubnbjn"/><path class="nkaqy4bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cross-math" /></template>
<style>
.ayashnh_b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 5.5h12.334v37H17.833z");
}

.aylyldbyl {
  cx: 36.333px;
  cy: 22.013px;
  r: 0.75px;
  fill: currentColor;
}

.d-889th1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.475 22.65c0-.447.17-.852.447-1.144A1.48 1.48 0 0 1 24 21.03c.842 0 1.525.725 1.525 1.619c0 .447-.142.885-.447 1.145c-.315.268-1.084.708-1.08 1.393l.002.22M10.167 24h3");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.nkaqy4bdi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.638 13.84c.31.416.783.701 1.567.701h.131c1.029 0 1.865-.852 1.863-1.904l-.005-1.941m-15.569.971h2.75M24 10.292v2.75m-11.179 1.499v-5.75l-3.018 3.862h3.725");
}

.vmmqegbrt {
  cx: 36.333px;
  cy: 25.987px;
  r: 0.75px;
  fill: currentColor;
}

.vmwnxib_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 17.833h37v12.334h-37zm29.159 20.891c.386.333.802.485 1.736.485h.218c.77 0 1.395-.643 1.395-1.437s-.624-1.437-1.395-1.437m-1.954-2.396c.386-.332.803-.483 1.737-.48l.217.001c.771 0 1.396.643 1.396 1.437s-.625 1.437-1.395 1.437m-13.914-1.3l2.6 2.6m0-2.6l-2.6 2.6m-12.896-2.27c0-1.176 1.042-2.102 2.232-1.868c.782.153 1.405.844 1.483 1.653c.058.603-.128 1.197-.535 1.562c-.754.676-3.18 2.498-3.18 2.498h3.725");
}

.wse7k0x-m {
  cx: 24px;
  cy: 26.917px;
  r: 0.75px;
  fill: currentColor;
}

.wu3zbts9r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.583 24h3.5");
}

.xsqubnbjn {
  cx: 36.332px;
  cy: 10.654px;
  r: 1.863px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
