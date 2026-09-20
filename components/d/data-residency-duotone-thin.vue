<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xraocd5qw"/><path class="s78ap7_nj"/><path class="el753yuux"/><path class="a3ch5yb2h"/><path class="gj3ndm0la"/><path class="n8uuobb1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:data-residency-duotone-thin" /></template>
<style>
.a3ch5yb2h {
  d: path("M5 10h10");
}

.el753yuux {
  d: path("M4 10a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.gj3ndm0la {
  d: path("M15 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n8uuobb1z {
  d: path("M18 18v3");
}

.s78ap7_nj {
  fill: currentColor;
  d: path("M15 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xraocd5qw {
  fill: currentColor;
  d: path("M4 10a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
