<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="fiihs3-8t"/><path class="bsc0zcipb"/><path class="bbfecwvte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-week-number-sharp" /></template>
<style>
.bbfecwvte {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 17.5h.01m3.99 0h.01m3.99 0h.01");
}

.bsc0zcipb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 12.5h10.5V15H6.75z");
}

.fiihs3-8t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 5.25h16.5v15H3.75zm0 4.75h16.5M8 2.75v4.5m8-4.5v4.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
