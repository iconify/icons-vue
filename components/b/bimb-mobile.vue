<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="psgn5ijgq"/><path class="segadcbnw"/><circle class="psgn5ijgq"/><path class="f0e6e8bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bimb-mobile" /></template>
<style>
.f0e6e8bwn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.776 20.04a8.5 8.5 0 0 1 3.363-.69c4.654 0 8.441 3.787 8.441 8.441a8.44 8.44 0 0 1-8.441 8.442a8.5 8.5 0 0 1-3.363-.69");
}

.psgn5ijgq {
  cx: 27.796px;
  cy: 27.796px;
  r: 11.908px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.segadcbnw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 12.092c-2.973 0-5.743.84-8.113 2.276V12.09A7.59 7.59 0 0 0 8.296 4.5v23.296C8.296 36.469 15.326 43.5 24 43.5s15.704-7.03 15.704-15.704S32.674 12.092 24 12.092");
}

</style>
