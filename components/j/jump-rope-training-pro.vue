<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zguuxu9su"/><circle class="r2v_rka9l"/><circle class="rb25mxgjy"/><circle class="lhvk6xbyf"/><path class="wv13-9b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jump-rope-training-pro" /></template>
<style>
.lhvk6xbyf {
  cx: 24px;
  cy: 18.598px;
  r: 4.058px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r2v_rka9l {
  cx: 24px;
  cy: 18.598px;
  r: 14.098px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rb25mxgjy {
  cx: 24px;
  cy: 18.598px;
  r: 9.078px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wv13-9b5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.532 32.696h4.74v8.435a2.37 2.37 0 0 1-2.37 2.369h0a2.37 2.37 0 0 1-2.37-2.37zm28.197 0h4.739v8.435a2.37 2.37 0 0 1-2.37 2.369h0a2.37 2.37 0 0 1-2.37-2.37z");
}

.zguuxu9su {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.902 18.598v14.098m28.196-14.098v14.098");
}

</style>
