<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f2yjju4lp"/><path class="j7p47fbty"/></g><g class="y9tr6bcfx"><circle class="h6-b4mb5b"/><path class="df2suxbmc"/><circle class="blzccvbbb"/><path class="glo3x7b3m"/></g><path class="e4ql6jvaa"/><path class="v_l02ub1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:huk-kwgt" /></template>
<style>
.blzccvbbb {
  cx: 32.115px;
  cy: 18.11px;
  r: 5.625px;
}

.df2suxbmc {
  d: path("m10.267 18.366l11.114-1.442m-1.728.462a2.292 2.292 0 1 1-4.45.578");
}

.e4ql6jvaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.43 43.327A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24c0-4.91 1.646-9.435 4.415-13.054h0c.36-4.224-.69-8.446-.69-8.446s4.695-.165 7.001 2.892V5.39A21.4 21.4 0 0 1 24 2.5a21.4 21.4 0 0 1 10.775 2.89l-.001.002C37.08 2.335 41.776 2.5 41.776 2.5s-1.052 4.222-.691 8.446h0A21.4 21.4 0 0 1 45.5 24c0 3.383-.782 6.584-2.174 9.431");
}

.f2yjju4lp {
  cx: 38.5px;
  cy: 38.5px;
  r: 7px;
}

.glo3x7b3m {
  d: path("m37.733 18.366l-11.114-1.442m1.728.462a2.292 2.292 0 1 0 4.45.578");
}

.h6-b4mb5b {
  cx: 15.885px;
  cy: 18.11px;
  r: 5.625px;
}

.j7p47fbty {
  d: path("M36.654 34.492v8.016m3.692 0v-2.053L38.273 38.5l2.073-1.955v-2.053");
}

.v_l02ub1l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.26 30.02l2.299-4.412a6.5 6.5 0 0 0-3.587-1.075a6.5 6.5 0 0 0-3.531 1.075l2.3 4.413c.53 1.018 1.987 1.018 2.518 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
