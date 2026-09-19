<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ulece9bii"/><g class="y9tr6bcfx"><circle class="gdj9o5b8d"/><path class="tlu0bcbzk"/></g><path class="n5evpxuba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:9kwcaptcha" /></template>
<style>
.gdj9o5b8d {
  cx: 13.99px;
  cy: 22.176px;
  r: 3.581px;
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

.n5evpxuba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.735 18.595v10.81m.001-2.296l4.894-4.87m-3.336 3.32l3.847 3.83");
}

.tlu0bcbzk {
  d: path("M10.726 28.087c.596.781 1.506 1.318 3.013 1.318h.251a3.58 3.58 0 0 0 3.581-3.58v-3.65");
}

.ulece9bii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.591 22.243l-2.23 7.162l-2.23-7.162l-2.229 7.162l-2.23-7.162");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
