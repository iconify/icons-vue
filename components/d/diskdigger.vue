<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="btm52kxfn"/><path class="rbt1mzbkr"/><circle class="qg3zycciw"/><circle class="x5iopibri"/><path class="l95-7rlpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:diskdigger" /></template>
<style>
.btm52kxfn {
  width: 28.977px;
  height: 7.639px;
  x: 5.5px;
  y: 31.831px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.015px;
  ry: 1.015px;
}

.l95-7rlpk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.09 33.015l-7.421-7.422a1.997 1.997 0 1 1 2.825-2.825l7.42 7.422");
}

.qg3zycciw {
  cx: 25.387px;
  cy: 17.022px;
  r: 8.493px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rbt1mzbkr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.264 32.253l-2.049-6.109m-.945-2.8l-.04-.153l-1.613-4.8a.93.93 0 0 0-.893-.639H11.26a.94.94 0 0 0-.903.64L5.699 32.243m1.109-3.29h26.337m-2.765 5.908H9.981");
}

.x5iopibri {
  cx: 40.502px;
  cy: 31.602px;
  r: 1.998px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
