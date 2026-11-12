<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="lqrlnfbtg"/><circle class="mvk5gbb7t"/><circle class="ov9m4obnk"/><circle class="out3f_12j"/><circle class="y-b52abdh"/><circle class="rhe-p1bon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grip-vertical-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lqrlnfbtg {
  cx: 8.488px;
  cy: 5px;
  r: 0.75px;
}

.mvk5gbb7t {
  cx: 8.488px;
  cy: 12px;
  r: 0.75px;
}

.out3f_12j {
  cx: 15.496px;
  cy: 5px;
  r: 0.75px;
}

.ov9m4obnk {
  cx: 8.504px;
  cy: 19px;
  r: 0.75px;
}

.rhe-p1bon {
  cx: 15.512px;
  cy: 19px;
  r: 0.75px;
}

.y-b52abdh {
  cx: 15.496px;
  cy: 12px;
  r: 0.75px;
}

</style>
