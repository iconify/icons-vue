<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="lf47jn7qo"/><path class="zid0z72fa"/><path class="use-rmbfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chameleon" /></template>
<style>
.lf47jn7qo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12.5L5 9c.5-.9 1.5-1.25 2.5-1C9 7 11 6.5 13 6.75c3 .4 5.25 2.75 5.25 5.75c0 1.75-1.25 3-3 3H6c-1.75 0-3-1.25-3-3");
}

.use-rmbfv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 11.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zid0z72fa {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 13.75c1.75.5 2.75 2 2.5 3.75c-.25 1.5-1.75 2.25-3 1.75c-1-.4-1.25-1.6-.5-2.25c.6-.5 1.5-.25 1.5.5m-11-2l-1 4.25m6-4.25l1 4.25m-10.75 0h11.5");
}

</style>
