<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="jf60lda-p"/><path class="f4-a3xfdq"/><path class="hm-bgfqny"/><path class="xvlspstxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dishwasher" /></template>
<style>
.f4-a3xfdq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 7.25h16.5");
}

.hm-bgfqny {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 5h.01");
}

.jf60lda-p {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.xvlspstxg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 10.75h6m-6.25 4v3m3.25-3v3m3.25-3v3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
