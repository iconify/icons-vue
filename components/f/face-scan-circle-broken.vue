<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="so69kfbvn"/><path class="xxle25b4v"/><path class="y1e06ebnb"/><path class="nksxc6bkm"/><path class="aut1f7qcz"/><path class="wbw_ixbrw"/><ellipse class="yad62e0rw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:face-scan-circle-broken" /></template>
<style>
.aut1f7qcz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.8001 14C21.0047 17.9183 17.9183 21.0047 14 21.8");
}

.nksxc6bkm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 2.19995C17.9183 2.99526 21.0047 6.08163 21.8001 9.99995");
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.so69kfbvn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 16C9.85038 16.6303 10.8846 17 12 17C13.1154 17 14.1496 16.6303 15 16");
}

.wbw_ixbrw {
  d: path("M15.5 10.5C15.5 11.0523 15.2761 11.5 15 11.5C14.7239 11.5 14.5 11.0523 14.5 10.5C14.5 9.94772 14.7239 9.5 15 9.5C15.2761 9.5 15.5 9.94772 15.5 10.5Z");
}

.xxle25b4v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.2002 10C2.99557 6.08169 6.08198 2.99533 10.0003 2.20001");
}

.y1e06ebnb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.0003 21.8C6.08198 21.0047 2.99557 17.9183 2.2002 14");
}

.yad62e0rw {
  cx: 9px;
  cy: 10.5px;
  rx: 0.5px;
  ry: 1px;
}

</style>
