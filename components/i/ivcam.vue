<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="hp6wstbjf"/><circle class="mcvxjsbsv"/><circle class="tzhejz1ir"/><path class="p8qyb2qiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ivcam" /></template>
<style>
.hp6wstbjf {
  cx: 24px;
  cy: 20px;
  r: 15.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mcvxjsbsv {
  cx: 24px;
  cy: 20px;
  r: 10px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p8qyb2qiy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 38.182c-3.035 0-5.784.344-7.894.953c-1.055.304-1.954.67-2.676 1.163s-1.328 1.2-1.328 2.062c0 .63.615 1.14 1.373 1.14h21.05c.758 0 1.373-.51 1.373-1.14c0-.862-.606-1.57-1.328-2.062s-1.622-.859-2.676-1.163c-2.11-.61-4.859-.953-7.894-.953");
}

.tzhejz1ir {
  cx: 28.572px;
  cy: 15.174px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
