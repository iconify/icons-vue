<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f_v_dfbgn"/><circle class="sfre88b8c"/><ellipse transform="rotate(-35.816 11.306 30.957)" class="ymso8lbki"/><path class="aukexgbcm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:automatoys" /></template>
<style>
.aukexgbcm {
  d: path("M30.688 29.099L20.08 36.206c7.636 2.046 11.208-.283 10.61-7.107");
}

.f_v_dfbgn {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

.sfre88b8c {
  cx: 29.916px;
  cy: 18.941px;
  r: 3.224px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ymso8lbki {
  cx: 11.306px;
  cy: 30.957px;
  rx: 2.478px;
  ry: 3.303px;
}

</style>
