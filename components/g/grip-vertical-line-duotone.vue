<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="rhe-p1bon"/><circle class="l9hq7bbcu"/><circle class="out3f_12j"/><circle class="ov9m4obnk"/><circle class="wgm5sqdww"/><circle class="lqrlnfbtg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grip-vertical-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l9hq7bbcu {
  cx: 15.512px;
  cy: 12px;
  r: 0.75px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.lqrlnfbtg {
  cx: 8.488px;
  cy: 5px;
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

.wgm5sqdww {
  cx: 8.504px;
  cy: 12px;
  r: 0.75px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
