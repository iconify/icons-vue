<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><circle class="kmnr8jx4o"/><path class="j6pk_fbfx"/><path class="l_ep1oxqq"/><path class="r0padj4iz"/><path class="wbw_ixbrw"/><ellipse class="yad62e0rw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:facemask-circle-linear" /></template>
<style>
.j6pk_fbfx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 20.5L17 15L13.857 13.7428C12.6649 13.266 11.3351 13.266 10.143 13.7428L7 15L7.5 20.5");
}

.kmnr8jx4o {
  cx: 12px;
  cy: 12px;
  r: 10px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l_ep1oxqq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 15L2.5 13");
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.r0padj4iz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 15L21.5 13");
}

.wbw_ixbrw {
  d: path("M15.5 10.5C15.5 11.0523 15.2761 11.5 15 11.5C14.7239 11.5 14.5 11.0523 14.5 10.5C14.5 9.94772 14.7239 9.5 15 9.5C15.2761 9.5 15.5 9.94772 15.5 10.5Z");
}

.yad62e0rw {
  cx: 9px;
  cy: 10.5px;
  rx: 0.5px;
  ry: 1px;
}

</style>
