<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rq-k-fb0w"/><circle class="ixollw7jt"/><path class="cekcrpb0u"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cricut-design-space" /></template>
<style>
.cekcrpb0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.887 21.506v5.075m-4.724-3.237c0-1.05.874-1.925 1.924-1.925m-1.925.087v5.075m22.576-6.65v5.688c0 .525.35.962.962.962h.262m-2.274-5.162h2.1m-9.188.087v3.15c0 1.05.875 1.925 1.925 1.925s1.925-.875 1.925-1.925v-3.15m0 3.238v1.837");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ixollw7jt {
  cx: 19.887px;
  cy: 19.231px;
  r: 0.75px;
  fill: currentColor;
}

.rq-k-fb0w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.1 25.619c-.262.525-.962.962-1.575.962A1.94 1.94 0 0 1 8.6 24.656v-1.225c0-1.05.875-1.925 1.925-1.925c.7 0 1.313.35 1.575.963m14.613 3.15c-.263.525-.963.962-1.576.962a1.94 1.94 0 0 1-1.925-1.925v-1.225c0-1.05.875-1.925 1.925-1.925c.7 0 1.313.35 1.575.963");
}

</style>
