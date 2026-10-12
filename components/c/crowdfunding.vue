<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="mx0ir3bdi"/><path class="uffq2-buh"/><circle class="clm4m9vec"/><circle class="fxb6qsbdu"/><circle class="h9gbjwb4c"/><path class="m-pbxlbqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crowdfunding" /></template>
<style>
.clm4m9vec {
  cx: 4.75px;
  cy: 15.25px;
  r: 1.5px;
}

.fxb6qsbdu {
  cx: 12px;
  cy: 15.25px;
  r: 1.5px;
}

.h9gbjwb4c {
  cx: 19.25px;
  cy: 15.25px;
  r: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-pbxlbqb {
  d: path("M2.75 21.25a2 1.5 0 0 1 4 0m3.25 0a2 1.5 0 0 1 4 0m3.25 0a2 1.5 0 0 1 4 0");
}

.mx0ir3bdi {
  cx: 12px;
  cy: 6.75px;
  r: 4px;
}

.uffq2-buh {
  d: path("M13.13 5.77c-.21-.45-.62-.75-1.12-.75c-.67 0-1.17.39-1.17.86c0 1.22 2.34.61 2.34 1.78c0 .49-.5.83-1.17.83c-.52 0-.96-.28-1.14-.73");
}

</style>
