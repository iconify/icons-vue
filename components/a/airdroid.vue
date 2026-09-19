<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="halvizbxz"/><path class="ry1z3ewgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:airdroid" /></template>
<style>
.halvizbxz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 9.731L4.5 24h28.632zm-7.497 2.742l1.18-4.736L4.5 24m39 14.269L4.5 24h28.632z");
}

.ry1z3ewgp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.003 35.526l1.18 4.737L4.5 24");
}

</style>
