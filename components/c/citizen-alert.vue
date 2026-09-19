<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h0e39rbxh"/><circle class="vly33-bpl"/><path class="vmdnxxbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:citizen-alert" /></template>
<style>
.h0e39rbxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.997 19.357a4.643 4.643 0 1 0 0 9.286v5.854C9.2 34.497 4.5 29.797 4.5 24s4.7-10.497 10.497-10.497z");
}

.vly33-bpl {
  cx: 24px;
  cy: 24px;
  r: 4.257px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vmdnxxbou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.003 19.357a4.643 4.643 0 1 1 0 9.286v5.854C38.8 34.497 43.5 29.797 43.5 24s-4.7-10.497-10.497-10.497z");
}

</style>
