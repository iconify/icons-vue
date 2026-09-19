<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="m2skeh2jo"/><path class="zpjz4ilxr"/></g><path class="gdpz_rbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-fossify-9" /></template>
<style>
.gdpz_rbbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.532 9.567h24.936a4 4 0 0 1 4 4V38.5a4 4 0 0 1-4 4H11.532a4 4 0 0 1-4-4V13.567a4 4 0 0 1 4-4M13.715 5.5v4.068M34.14 5.5v4.068M9.731 19.89h28.36");
}

.m2skeh2jo {
  cx: 24px;
  cy: 29.329px;
  r: 3.733px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zpjz4ilxr {
  d: path("M20.681 35.413c.554.83 1.521 1.382 3.042 1.382H24a3.72 3.72 0 0 0 3.733-3.733v-3.733");
}

</style>
