<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGUyEhLdAt" x1="2.7" x2="25.2" y1="7.1" y2="29.5" gradientTransform="matrix(1.245 0 0 .9459 -1.4 -1.3)" gradientUnits="userSpaceOnUse"><stop offset="0" class="gl-tvki0d"/><stop offset=".5" class="qegxe2bjj"/><stop offset="1" class="q6oxmbcor"/></linearGradient></defs><rect stroke="url(#SVGUyEhLdAt)" class="u6prt5guj"/><g class="rx4r5nije"><rect class="qolc3ac9m"/><circle class="r7af_r0if"/><circle class="ld1grcc4i"/><circle class="g9lrdwboz"/></g><path class="cvku5l74s"/><g class="rx4r5nije"><rect class="bly8j_o6c"/><rect class="c4yn1tbnp"/><rect class="bd1iep7lq"/><rect class="jj_83xb-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-mise" /></template>
<style>
.bd1iep7lq {
  width: 6.1px;
  height: 0.9px;
  x: 14.6px;
  y: 20.6px;
  fill: var(--svg-color--ff9100, #ff9100);
  opacity: var(--svg-opacity--0-6, 0.6);
  rx: 0.4px;
}

.bly8j_o6c {
  width: 11.8px;
  height: 0.9px;
  x: 13.2px;
  y: 14.5px;
  fill: var(--svg-color--00d9ff, #00d9ff);
  opacity: var(--svg-opacity--0-7, 0.7);
  rx: 0.4px;
}

.c4yn1tbnp {
  width: 8.5px;
  height: 0.9px;
  x: 5.1px;
  y: 20.6px;
  fill: var(--svg-color--52e892, #52e892);
  opacity: var(--svg-opacity--0-6, 0.6);
  rx: 0.4px;
}

.cvku5l74s {
  fill: none;
  stroke: var(--svg-color--52e892, #52e892);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("m5 15.5l2.3 1.6L5 18.8m3.8 0H12");
}

.g9lrdwboz {
  cx: 14.5px;
  cy: 8.9px;
  r: 1px;
  fill: var(--svg-color--52e892, #52e892);
}

.gl-tvki0d {
  stop-color: var(--svg-color--00d9ff, #00d9ff);
}

.jj_83xb-q {
  width: 12.8px;
  height: 0.9px;
  x: 5.1px;
  y: 23.3px;
  fill: var(--svg-color--00d9ff, #00d9ff);
  opacity: var(--svg-opacity--0-4, 0.4);
  rx: 0.4px;
}

.ld1grcc4i {
  cx: 10.5px;
  cy: 8.9px;
  r: 1px;
  fill: var(--svg-color--ffbd2e, #ffbd2e);
}

.q6oxmbcor {
  stop-color: var(--svg-color--ff9100, #ff9100);
}

.qegxe2bjj {
  stop-color: var(--svg-color--52e892, #52e892);
}

.qolc3ac9m {
  width: 26.1px;
  height: 5.4px;
  x: 2.9px;
  y: 6.3px;
  fill: var(--svg-color--2a2a2a, #2a2a2a);
  rx: 2.1px;
}

.r7af_r0if {
  cx: 6.5px;
  cy: 8.9px;
  r: 1px;
  fill: var(--svg-color--ff5252, #ff5252);
}

.rx4r5nije {
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
}

.u6prt5guj {
  width: 27px;
  height: 20.3px;
  x: 2.5px;
  y: 5.9px;
  fill: var(--svg-color--1a1a1a, #1a1a1a);
  rx: 2.7px;
}

</style>
