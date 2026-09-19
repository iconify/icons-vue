<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ld3m-xblo"/><circle class="zc13o1bio"/><circle class="bzu6gcchc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alliant" /></template>
<style>
.bzu6gcchc {
  cx: 24px;
  cy: 19.125px;
  r: 9.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ld3m-xblo {
  cx: 14.25px;
  cy: 28.875px;
  r: 9.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zc13o1bio {
  cx: 33.75px;
  cy: 28.875px;
  r: 9.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
