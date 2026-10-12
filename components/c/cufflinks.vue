<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="jc6oap-gd"/><circle class="dx6qgibjz"/><path class="rwplwb62a"/><rect class="ig_-qpv2p"/><rect class="i_rqi5bwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cufflinks" /></template>
<style>
.dx6qgibjz {
  cx: 17.5px;
  cy: 8.5px;
  r: 3.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_rqi5bwp {
  width: 5.5px;
  height: 2.5px;
  x: 14.75px;
  y: 17.5px;
  rx: 1.25px;
}

.ig_-qpv2p {
  width: 5.5px;
  height: 2.5px;
  x: 3.75px;
  y: 17.5px;
  rx: 1.25px;
}

.jc6oap-gd {
  cx: 6.5px;
  cy: 8.5px;
  r: 3.75px;
}

.rwplwb62a {
  d: path("M6.5 12.25v5.25m11-5.25v5.25");
}

</style>
