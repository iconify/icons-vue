<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ygm05n-tt"/><path class="d2ifwcbbf"/><path class="zc_41vubh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:joker-card" /></template>
<style>
.d2ifwcbbf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 18h8.5q.75 0 .75-.75v-5q0-.75-.56-.25l-1.38 1.25q-.56.5-1.02-.09l-1.58-2.07q-.46-.59-.92 0l-1.58 2.07q-.46.59-1.02.09L7.56 12q-.56-.5-.56.25v5q0 .75.75.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ygm05n-tt {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.25px;
}

.zc_41vubh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 9h.01M17 9h.01M12 8h.01");
}

</style>
