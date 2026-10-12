<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xa4js6bqn"/><path class="erxuqhbij"/><circle class="j6_2s9b6i"/><circle class="ir2sjacxb"/><circle class="dra-ew7oo"/><circle class="e_ly2_bkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:garland-flowers-sharp" /></template>
<style>
.dra-ew7oo {
  cx: 12px;
  cy: 9.5px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.e_ly2_bkx {
  cx: 12px;
  cy: 18.75px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.erxuqhbij {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.47 15.25h.01m11.05 0h.01");
}

.ir2sjacxb {
  cx: 17.53px;
  cy: 8.34px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6_2s9b6i {
  cx: 6.47px;
  cy: 8.34px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xa4js6bqn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 5l.704 1.408L4.84 7.42m3.41 1.59c.61.17 1.25.29 1.9.37m3.7 0c.65-.08 1.29-.2 1.9-.37m3.41-1.59l1.386-1.012L21.25 5M6.47 10.1v3.4m11.06-3.4v3.4M12 11.25v4.5");
}

</style>
