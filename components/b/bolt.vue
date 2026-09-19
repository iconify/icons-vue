<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="usv6s579o"/><path class="jcfc8_bai"/><circle class="zl285sv_h"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bolt" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.jcfc8_bai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.9 24h6c2 0 3.6 1.6 3.6 3.6h0c0 2-1.6 3.6-3.6 3.6h-6m15.5 0c-2 0-3.6-1.6-3.6-3.6v-2.2c0-2 1.6-3.6 3.6-3.6h0c2 0 3.6 1.6 3.6 3.6v2.2c0 2-1.6 3.6-3.6 3.6m10-12.4v10.6c0 1 .8 1.8 1.8 1.8h.7m-6.6-14.4v14.4m2.2-9.4h1.9m0 0h1.9");
}

.usv6s579o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.9 31.2V16.8m0 0h6c2 0 3.6 1.6 3.6 3.6h0c0 2-1.6 3.6-3.6 3.6h-6");
}

.zl285sv_h {
  cx: 25.4px;
  cy: 33.3px;
  r: 0.8px;
  fill: currentColor;
}

</style>
