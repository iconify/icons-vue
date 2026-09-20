<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vdkk_bbqh"/><path class="jy2rzibrh"/><path class="fgqk6gbgn"/><path class="qh6hkcycj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:attending-duotone-thin" /></template>
<style>
.fgqk6gbgn {
  d: path("M2.4 16a6.6 6.6 0 0 1 13.2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jy2rzibrh {
  d: path("M6 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.qh6hkcycj {
  d: path("m15 16 2 2 4 -4");
}

.vdkk_bbqh {
  fill: currentColor;
  d: path("M6 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
