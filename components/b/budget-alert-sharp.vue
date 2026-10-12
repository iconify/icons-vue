<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="uv9lvcbqh"/><path class="vop2enb6d"/><circle class="gqdwd_bjh"/><path class="ljumwebzv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:budget-alert-sharp" /></template>
<style>
.gqdwd_bjh {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ljumwebzv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.38 16.27l-.35-.75h-1.94v.86c0 1.22 2.34.61 2.34 1.78v.83h-2.018l-.292-.73");
}

.uv9lvcbqh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 21.25h-7.5V2.75h14v8.5m-10.5-4.5h7.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vop2enb6d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 11.25h.01m3.24 0h.01m-3.26 3.5h.01M7.75 18h.01");
}

</style>
