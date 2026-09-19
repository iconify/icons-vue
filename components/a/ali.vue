<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="dnk3fbbmu"/><circle class="b05pxb1-h"/><path class="ndnq7woly"/><ellipse class="mf3q1jixn"/><ellipse class="gj-gue9bw"/><path class="dmqrqacon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ali" /></template>
<style>
.b05pxb1-h {
  cx: 24px;
  cy: 4.551px;
  r: 1.051px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dmqrqacon {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.91 22.949c3.648-3.036 8.617.592 12.09.525s8.499-3.138 12.09-.525s3.093 11.586 0 14.718s-21.278 2.95-24.18 0c-2.901-2.951-3.648-11.682 0-14.718");
}

.dnk3fbbmu {
  cx: 24px;
  cy: 26.103px;
  r: 18.397px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gj-gue9bw {
  cx: 31.622px;
  cy: 32.936px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.84px;
  ry: 3.679px;
}

.mf3q1jixn {
  cx: 16.378px;
  cy: 32.936px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.84px;
  ry: 3.679px;
}

.ndnq7woly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.603V7.18");
}

</style>
