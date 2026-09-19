<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yf5qvbbvj"/><circle class="ft61xebgq"/><path class="udwkir1pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:encrypt-text" /></template>
<style>
.ft61xebgq {
  cx: 40.686px;
  cy: 23.236px;
  r: 3.565px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.udwkir1pd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.468 25.598l-10.08 7.397m3.048-2.237l1.823 2.447l-2.065 1.515l-1.805-2.46");
}

.yf5qvbbvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.251 12.61h37.554v4.241H5.251zm0 16.841h19.505v4.241H5.251zm0-8.421H33.33v4.241H5.251z");
}

</style>
