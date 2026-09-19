<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="lovuhby4g"/><ellipse class="ithd4eb-c"/><path class="bribo1bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blubank" /></template>
<style>
.bribo1bfa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.874 7.161v23.982");
}

.ithd4eb-c {
  cx: 24px;
  cy: 31.143px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 12.126px;
  ry: 12.357px;
}

.lovuhby4g {
  cx: 26.182px;
  cy: 6.556px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.061px;
  ry: 2.057px;
}

</style>
