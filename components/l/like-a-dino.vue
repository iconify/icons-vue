<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mxa002b6k"/><path class="cyc06j_hv"/><circle class="yxrav5bru"/><circle class="tnriovlnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:like-a-dino" /></template>
<style>
.cyc06j_hv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.752 29.939s6.322 6.235 13.053 1.163");
}

.mxa002b6k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.196 18.172c.459-10.217 19.877-16.964 27.151 2.157c6.566 18.864-16.426 22.457-29.754 17.41C2.71 35.079.033 21.554 15.196 18.17z");
}

.tnriovlnn {
  cx: 28.71px;
  cy: 17.604px;
  r: 0.75px;
  fill: currentColor;
}

.yxrav5bru {
  cx: 20.639px;
  cy: 16.388px;
  r: 0.75px;
  fill: currentColor;
}

</style>
