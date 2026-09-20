<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kjz9wmbes"/><path class="slmpunbln"/><path class="wxfc8bn6j"/><path class="oa7ibkb8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:liveness-duotone-bold" /></template>
<style>
.kjz9wmbes {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 6h3l2 -2 4 4 2 -2h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oa7ibkb8p {
  d: path("M14.32 10a5.5 5.5 0 1 1 -4.64 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.slmpunbln {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14.32 10a5.5 5.5 0 1 1 -4.64 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wxfc8bn6j {
  d: path("M5 6h3l2 -2 4 4 2 -2h3");
}

</style>
