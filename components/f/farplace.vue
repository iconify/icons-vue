<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hmyeoco9r"/><path class="dq_9h141t"/><path class="wwty9achx"/><path class="pqm4r9c4k"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:farplace" /></template>
<style>
.dq_9h141t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.257 12.137a8.4 8.4 0 0 1 2.228 1.822c0 1.563.231 17.944.231 17.944m4.463-2.278c1.527.307 3.234 2.535 3.321 4.792");
}

.hmyeoco9r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.586 35.111c.897 1.129 12.731-5.845 14.872-6.54");
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

.pqm4r9c4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.276 23.48c-2.2.694-7.35 3.616-7.35 3.616c-1.331-1.678-3.964-7.726-3.964-7.726m-5.672-3.848c3.241-.897 3.473-.752 3.589 0s-1.997 3.501-1.997 3.501M11.5 23.971c2.836.52 3.762-1.196 4.543-.974s-1.476 3.434-1.476 3.434m6.134-1.714c-.665 3.103-6.365 11.147-6.365 11.147c-1.852-.55-2.373-1.447-2.373-1.447");
}

.wwty9achx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.81 21.598c3.675-1.388 9.462-2.835 9.462-2.835c.492 1.823-1.736 8.16-2.836 8.449s-2.823-2.807-2.823-2.807");
}

</style>
