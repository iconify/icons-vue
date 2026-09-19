<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="niypo6vhc"/><path class="hykwetb7l"/><path class="l22hs482w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cube-escape-case-23" /></template>
<style>
.hykwetb7l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.003 24.032L6.163 13.729v20.468L24.003 44.5zm17.724-10.229L24.003 24.032V44.5l17.724-10.229zM26.735 10.35l6.772 3.91l-8.617 4.975l-6.773-3.91");
}

.l22hs482w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.982 10.295l-11.996-.021l.037 6.774");
}

.niypo6vhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.727 13.803L23.887 3.5L6.163 13.729l17.84 10.303z");
}

</style>
