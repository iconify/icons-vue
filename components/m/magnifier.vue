<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ilo6oobed"/><circle class="j417i3sfl"/><path class="ynt45xqli"/><circle class="j-lhhl9vm"/><circle class="n4tjbvb2u"/><path class="huwztac5y"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:magnifier" /></template>
<style>
.huwztac5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.816 39.832l3.029-2.185");
}

.ilo6oobed {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.363 41.293c-2.434-2.494-3.718-4.377-6.062-5.52l-1.48 1.041c.546 2.338.992 3.725 2.51 5.686m-1.786-6.194l-2.313-2.784");
}

.j-lhhl9vm {
  cx: 26.237px;
  cy: 18.705px;
  r: 2.387px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
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

.j417i3sfl {
  cx: 24px;
  cy: 24px;
  r: 12.587px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n4tjbvb2u {
  cx: 26.666px;
  cy: 23.974px;
  r: 0.582px;
  fill: currentColor;
}

.ynt45xqli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.516 24.363c1.472-7.258 5.543-11.155 14.062-10.4");
}

</style>
