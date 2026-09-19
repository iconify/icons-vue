<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="n07-xsbkm"/><g class="y9tr6bcfx"><path class="uw_g3xb7q"/><ellipse class="ke2lmob8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:goodwy-contacts" /></template>
<style>
.ke2lmob8g {
  cx: 24.002px;
  cy: 18.369px;
  rx: 6.64px;
  ry: 7.625px;
}

.n07-xsbkm {
  cx: 24.027px;
  cy: 24.013px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uw_g3xb7q {
  d: path("M27.373 24.937c5.604 1.056 7.926 3.89 7.926 3.89c.962 1.667 0 3.96 0 3.96c-3.25 4.046-8.181 4.471-11.297 4.471c-3.115 0-8.046-.425-11.296-4.471c0 0-.962-2.293 0-3.96c0 0 2.322-2.833 7.926-3.89");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
