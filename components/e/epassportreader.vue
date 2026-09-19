<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="yoo1prykp"/><circle class="s-tu1sj_i"/><path class="m18pmwbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:epassportreader" /></template>
<style>
.m18pmwbnx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.5 24h-13m26 0h13");
}

.s-tu1sj_i {
  cx: 24px;
  cy: 24px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yoo1prykp {
  width: 39px;
  height: 25px;
  x: 4.5px;
  y: 11.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.999px;
}

</style>
