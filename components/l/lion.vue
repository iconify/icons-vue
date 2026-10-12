<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="jd_3e8irj"/><path class="o347htb8v"/><path class="af9qykbbr"/><path class="e--ewzbst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lion" /></template>
<style>
.af9qykbbr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 12.25h.01m3.49 0h.01");
}

.e--ewzbst {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 14.25h2l-1 1Zm1 1c0 .75-.5 1.25-1.25 1.25M12 15.25c0 .75.5 1.25 1.25 1.25");
}

.jd_3e8irj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.39 4.63a2.5 2.5 0 0 1 3.88 2.81A2.5 2.5 0 0 1 19.75 12a2.5 2.5 0 0 1-1.48 4.56a2.5 2.5 0 0 1-3.88 2.81a2.5 2.5 0 0 1-4.78 0a2.5 2.5 0 0 1-3.88-2.81A2.5 2.5 0 0 1 4.25 12a2.5 2.5 0 0 1 1.48-4.56a2.5 2.5 0 0 1 3.88-2.81a2.5 2.5 0 0 1 4.78 0");
}

.o347htb8v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.26 10.73a1.5 1.5 0 1 1 1.72-1.72a4.25 4.25 0 0 1 4.04 0a1.5 1.5 0 1 1 1.72 1.72a4.25 4.25 0 1 1-7.48 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
