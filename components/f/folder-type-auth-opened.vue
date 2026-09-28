<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gpujsq5-g"/><g transform="matrix(1.14465 -.78383 .7697 1.16566 -6.01 2.614)"><rect transform="rotate(-.675)skewX(-.166)" class="r7306lblv"/><circle class="hp4825onv"/><rect transform="matrix(.99978 .02075 .0211 .99978 0 0)" class="e_oogkbmu"/><rect transform="matrix(.99968 .0254 .0054 .99999 0 0)" class="ehrifibxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-auth-opened" /></template>
<style>
.e_oogkbmu {
  width: 4.055px;
  height: 2.143px;
  x: 8.743px;
  y: 25.018px;
  fill: var(--svg-color--efc800, #efc800);
  ry: 0.727px;
}

.ehrifibxr {
  width: 2.716px;
  height: 2.142px;
  x: 9.213px;
  y: 22.057px;
  fill: var(--svg-color--efc800, #efc800);
  ry: 0.727px;
}

.gpujsq5-g {
  fill: var(--svg-color--5c4d00, #5c4d00);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

.hp4825onv {
  cx: 8.66px;
  cy: 16.119px;
  r: 3.199px;
  fill: none;
  stroke: var(--svg-color--efc800, #efc800);
  stroke-width: var(--svg-stroke-width--2-095px, 2.095px);
}

.r7306lblv {
  width: 2.799px;
  height: 10.513px;
  x: 7.214px;
  y: 18.782px;
  fill: var(--svg-color--a68b00, #a68b00);
  ry: 1.588px;
}

</style>
