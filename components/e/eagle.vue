<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="m01qpebot"/><path class="lzasjvbup"/><path class="wxvyht8eu"/><path class="bh4uq-bgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eagle" /></template>
<style>
.bh4uq-bgf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 11.75c.75 1.5 1.25 3 1.25 4.75");
}

.lzasjvbup {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 6c-2.25.25-4 1.75-4 4.25c0 .75.25 1.5.75 2C3.75 11 4.75 10.5 6 10.5l2.6-1.8");
}

.m01qpebot {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.25 9.5c-1.5-3.75-4.5-6.25-8.25-6.25c-2.5 0-4.75 1-6.25 2.75L9 9.25c.5 4.5 1.25 7.5 1.25 12H20C19.5 17.5 18.25 15 17 13c1.25-2 2.75-3 4.25-3.5");
}

.wxvyht8eu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.5 7.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
