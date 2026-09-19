<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="kcfd9fwmv"/><circle class="ohe1qbcou"/><path class="egw4bpbjd"/></g><path class="gdpz_rbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-fossify-16" /></template>
<style>
.egw4bpbjd {
  d: path("M31.085 26.978c-.554-.83-1.521-1.383-3.042-1.383h-.277a3.72 3.72 0 0 0-3.733 3.734v3.733");
}

.gdpz_rbbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.532 9.567h24.936a4 4 0 0 1 4 4V38.5a4 4 0 0 1-4 4H11.532a4 4 0 0 1-4-4V13.567a4 4 0 0 1 4-4M13.715 5.5v4.068M34.14 5.5v4.068M9.731 19.89h28.36");
}

.kcfd9fwmv {
  d: path("m17.318 27.135l2.8-1.54m0 0v11.2");
}

.ohe1qbcou {
  cx: 27.766px;
  cy: 33.062px;
  r: 3.733px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
