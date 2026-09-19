<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j1vmf_i1k"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-control-knobs" /></template>
<style>
.j1vmf_i1k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.038 15.505a3.88 3.88 0 1 1-3.723-4.03m-14.84 6.764a3.88 3.88 0 1 1 .296-5.478m17.134 22.631a3.88 3.88 0 1 1 0-5.487m-20.021-1.136a3.88 3.88 0 1 1-3.88 3.88m3.88-.001l-4.35-3.33m26.931 3.501l-5.303-.17M20.283 15.531l-5.57-.22m21.328-3.441l-3.88 3.482");
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

</style>
