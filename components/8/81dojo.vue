<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="cc6c1kbuz"/><path class="bhn42ltec"/></g><path class="pyy5adb1a"/><circle class="ww9jbmbwd"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:81dojo" /></template>
<style>
.bhn42ltec {
  d: path("M14.659 15.787a3.25 3.25 0 0 0 3.25-3.25h0a3.25 3.25 0 0 0-3.25-3.25h-2.113a3.25 3.25 0 0 0-3.25 3.25h0a3.25 3.25 0 0 0 3.25 3.25m0 0h2.113");
}

.cc6c1kbuz {
  d: path("M12.546 15.787a3.25 3.25 0 0 0-3.25 3.25h0a3.25 3.25 0 0 0 3.25 3.25h2.113a3.25 3.25 0 0 0 3.25-3.25h0a3.25 3.25 0 0 0-3.25-3.25");
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

.pyy5adb1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.159 11.057l3.25-1.77v13m-7.25 13.063v-8h1.8a3.5 3.5 0 0 1 3.5 3.5v1a3.5 3.5 0 0 1-3.5 3.5zm9.3.3a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v1.3a2 2 0 0 1-2 2m10 0a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v1.3a2 2 0 0 1-2 2m-4.868-5.15v6c0 1.105-.887 2-1.981 2h0a1.97 1.97 0 0 1-1.401-.586");
}

.ww9jbmbwd {
  cx: 31.591px;
  cy: 28.1px;
  r: 0.75px;
  fill: currentColor;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
