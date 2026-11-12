<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="xewxn_bct"/><path class="pjs0z5b6h"/><path class="l_ep1oxqq"/><path class="p8hlydmhp"/><path class="r0padj4iz"/><path class="nq9lwk--d"/><path class="wbw_ixbrw"/><ellipse class="yad62e0rw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:facemask-square-broken" /></template>
<style>
.l_ep1oxqq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 15L2.5 13");
}

.nq9lwk--d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 19L20.5 20.5");
}

.p8hlydmhp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 19L3.5 20.5");
}

.pjs0z5b6h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 21.5L17 15L13.857 13.7428C12.6649 13.266 11.3351 13.266 10.143 13.7428L7 15L7.5 21.5");
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

.xewxn_bct {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.43821 2.49073 5.80655 2.16444 8 2.0551");
}

.yad62e0rw {
  cx: 9px;
  cy: 10.5px;
  rx: 0.5px;
  ry: 1px;
}

</style>
