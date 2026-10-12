<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ae3t-3b0n"/><path class="ze_7_bn1z"/><circle class="u1v_qsbkd"/><path class="rcbntwbcw"/><circle class="at-v-ac8j"/><path class="rlar09bwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crane-mobile-sharp" /></template>
<style>
.ae3t-3b0n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15.5v-3l.67-1.05l.41-.65l.67-1.05h4v3.5h12.75v3.5H2.75z");
}

.at-v-ac8j {
  cx: 15.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rcbntwbcw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 19h.01");
}

.rlar09bwl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.5 19h.01");
}

.u1v_qsbkd {
  cx: 8.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.ze_7_bn1z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.5 9.75l12.5-6v6h-2v-1m-15.75 8v4.5m17.5-4.5v4.5");
}

</style>
