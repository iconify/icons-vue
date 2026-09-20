<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="f1ihv1bbc"/><path class="b-t1ysbiw"/><path class="b4w1prb2a"/><circle class="s7-gkgbhj"/><circle class="oisfnzbzm"/><circle class="a-ph0hz2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:linwood-flow" /></template>
<style>
.a-ph0hz2e {
  cx: 10.138px;
  cy: 13.845px;
  r: 0.75px;
  fill: currentColor;
}

.b-t1ysbiw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.979 39.889h6.912a9.176 9.176 0 0 0 9.175-9.176v-5.868a9.12 9.12 0 0 0-1.76-5.389a5.682 5.682 0 1 0-5.771-3.632a9 9 0 0 0-1.644-.155H17.067a9 9 0 0 0-1.644.155a5.655 5.655 0 1 0-5.771 3.632a9.12 9.12 0 0 0-1.76 5.39v5.867a9.176 9.176 0 0 0 9.175 9.176z");
}

.b4w1prb2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.066 30.713H23.98v-4H7.89");
}

.f1ihv1bbc {
  cx: 10.138px;
  cy: 13.845px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oisfnzbzm {
  cx: 37.819px;
  cy: 13.845px;
  r: 0.75px;
  fill: currentColor;
}

.s7-gkgbhj {
  cx: 37.819px;
  cy: 13.845px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
