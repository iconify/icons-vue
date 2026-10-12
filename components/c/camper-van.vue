<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="g2kgttbgm"/><path class="dwixvm2-u"/><path class="nmn-xr-bu"/><circle class="z38jf6blv"/><path class="pfp4ny3fh"/><circle class="mc5frpbkh"/><path class="sv-1mv4il"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camper-van" /></template>
<style>
.dwixvm2-u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7h9.75q2 0 3.41 1.41l1.93 1.93q1.41 1.41 1.41 3.41v1q0 2-2 2H4.75q-2 0-2-2V9q0-2 2-2");
}

.g2kgttbgm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.03 6.3l.94-2.35q.28-.7 1.03-.7h6q.75 0 1.03.7l.94 2.35q.28.7-.47.7h-9q-.75 0-.47-.7");
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

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z38jf6blv {
  cx: 7.25px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
