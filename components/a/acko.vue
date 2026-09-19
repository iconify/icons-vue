<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="kf2-t-i6d"/><path class="i40am8epl"/><rect class="a8l8hrvoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:acko" /></template>
<style>
.a8l8hrvoz {
  width: 41px;
  height: 17.656px;
  x: 3.5px;
  y: 15.172px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.828px;
  ry: 8.828px;
}

.i40am8epl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.299 20.128v7.766m4.395-.018l-4.391-3.865l4.391-3.887m-7.37 6.294a2.93 2.93 0 0 1-2.544 1.476h0a2.93 2.93 0 0 1-2.93-2.93v-1.905a2.93 2.93 0 0 1 2.93-2.931h0a2.93 2.93 0 0 1 2.541 1.47m-8.502 3.354a2.93 2.93 0 0 1-2.93 2.93h0a2.93 2.93 0 0 1-2.931-2.93v-1.904a2.93 2.93 0 0 1 2.93-2.93h0a2.93 2.93 0 0 1 2.93 2.93m.001 4.835v-4.835");
}

.kf2-t-i6d {
  width: 5.861px;
  height: 7.766px;
  x: 33.181px;
  y: 20.128px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.93px;
  ry: 2.93px;
}

</style>
