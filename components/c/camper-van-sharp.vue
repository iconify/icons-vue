<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jzmy6be_y"/><path class="yzi-a343q"/><path class="nmn-xr-bu"/><circle class="z38jf6blv"/><path class="pfp4ny3fh"/><circle class="mc5frpbkh"/><path class="sv-1mv4il"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camper-van-sharp" /></template>
<style>
.jzmy6be_y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.03 6.3l.94-2.35l.28-.7h7.5l.28.7l.94 2.35l.28.7H4.75z");
}

.mc5frpbkh {
  cx: 16.75px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nmn-xr-bu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 10h5v2.5h-5Zm8.25.5h2l1.5 1.75");
}

.pfp4ny3fh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 19h.01");
}

.sv-1mv4il {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 19h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yzi-a343q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7H16.5l1.41 1.41l1.93 1.93l1.41 1.41v5H2.75V7z");
}

.z38jf6blv {
  cx: 7.25px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
