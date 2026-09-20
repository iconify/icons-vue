<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j6br2vbzt"/><path class="dmzb83bqo"/><path class="xmuq15b2m"/><path class="xk9h6b9ga"/><path class="v3-0b9bnr"/><path class="zf7mx_7mn"/><path class="ufignx6hm"/><path class="cy34vrbps"/><path class="ooykrqbbx"/><path class="t3p_xpene"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bucket-data-duotone-thin" /></template>
<style>
.cy34vrbps {
  d: path("M10 8.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dmzb83bqo {
  fill: currentColor;
  d: path("M15.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6br2vbzt {
  fill: currentColor;
  d: path("M4.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ooykrqbbx {
  d: path("M3 13v7h7v-7");
}

.t3p_xpene {
  d: path("M14 13v7h7v-7");
}

.ufignx6hm {
  d: path("M15.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.v3-0b9bnr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 13v7h7v-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xk9h6b9ga {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 13v7h7v-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xmuq15b2m {
  fill: currentColor;
  d: path("M10 8.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zf7mx_7mn {
  d: path("M4.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
