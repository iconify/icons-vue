<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bq9mex9td"/><path class="egt95gvne"/><path class="acja6ya7a"/><path class="neabk9byu"/><path class="mqk-0xbiv"/><path class="zoz5ar7wf"/><path class="tazaw9t8u"/><path class="quwwt_b4w"/><path class="ffs26fbkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dep-graph-duotone-bold" /></template>
<style>
.acja6ya7a {
  fill: currentColor;
  d: path("M9 14a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.bq9mex9td {
  fill: currentColor;
  d: path("M2 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.egt95gvne {
  fill: currentColor;
  d: path("M16 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ffs26fbkv {
  d: path("M12 17v4");
}

.mqk-0xbiv {
  d: path("M16 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.neabk9byu {
  d: path("M2 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.quwwt_b4w {
  d: path("M16.5 9.5 14 12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tazaw9t8u {
  d: path("M7.5 9.5 10 12");
}

.zoz5ar7wf {
  d: path("M9 14a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
