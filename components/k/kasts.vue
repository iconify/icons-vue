<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="d2bol5iee"/><path class="ikw9ebc_g"/><path class="pjmt7h7do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kasts" /></template>
<style>
.d2bol5iee {
  cx: 24px;
  cy: 18.805px;
  r: 3.27px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ikw9ebc_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.945 21.935L32.472 43.5m-9.417-21.565L15.527 43.5m11.126-16.672l-7.105 5.154l11.887 8.545M29.586 25.32a8.583 8.583 0 1 0-10.999.145");
}

.pjmt7h7do {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.368 31.068a14.304 14.304 0 1 0-14.704.019");
}

</style>
