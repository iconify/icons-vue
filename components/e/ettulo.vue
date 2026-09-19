<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v0gkmjb4t"/><g class="y9tr6bcfx"><circle class="bp_qm8bhz"/><path class="tb45lbbtg"/></g><g class="y9tr6bcfx"><path class="ehei_ieqa"/><path class="tk4fczc3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ettulo" /></template>
<style>
.bp_qm8bhz {
  cx: 24px;
  cy: 15.428px;
  r: 2.8px;
}

.ehei_ieqa {
  d: path("M20.839 38.275V36.56a3.161 3.161 0 1 1 6.322 0v1.714");
}

.tb45lbbtg {
  d: path("M29.4 23.628a5.4 5.4 0 0 0-10.8 0z");
}

.tk4fczc3g {
  d: path("M22.987 37.539v-.793a1.014 1.014 0 0 1 2.027 0v2.597m-2.028-.19v.807");
}

.v0gkmjb4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.5 41.5v-35c0-1.1-.9-2-2-2h-19c-1.1 0-2 .9-2 2v35c0 1.1.9 2 2 2h19c1.1 0 2-.9 2-2");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
