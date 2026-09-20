<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ribydbbyb"/><path class="vlzy6-bwf"/><circle class="so7f-6b0l"/><path class="rbqwh11kz"/><circle class="vn1_kc12c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:360-online-20" /></template>
<style>
.rbqwh11kz {
  d: path("M26.377 15.304c-.504-.756-1.385-1.26-2.77-1.26h-.253c-1.89 0-3.4 1.512-3.4 3.275v3.527m16.979-5.839l-4.969 7.578m2.519 1.133zc-1.89 0-3.4-1.511-3.4-3.275v-3.4c0-1.89 1.51-3.275 3.274-3.275c1.89 0 3.275 1.511 3.275 3.274v3.401c.252 1.89-1.26 3.275-3.149 3.275");
}

.ribydbbyb {
  d: path("M4.5 25.814q20.226 5.093 39 0V37.21h-39zm4.974-2.906c.756.63 1.386.882 3.149.882h.378a2.527 2.527 0 0 0 2.519-2.52A2.527 2.527 0 0 0 13 18.751");
}

.so7f-6b0l {
  cx: 23.355px;
  cy: 20.846px;
  r: 3.401px;
}

.vlzy6-bwf {
  d: path("M9.474 14.595c.756-.63 1.512-.882 3.149-.882h.378a2.527 2.527 0 0 1 2.519 2.519a2.527 2.527 0 0 1-2.52 2.52m-1.889-.001h1.89");
}

.vn1_kc12c {
  cx: 42.063px;
  cy: 11.923px;
  r: 1.134px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
