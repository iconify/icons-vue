<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f0eu_912v"/><path class="nzfvycb-k"/><path class="r182r524c"/><path class="c7z9o8buo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:energy-level-duotone-thin" /></template>
<style>
.c7z9o8buo {
  d: path("M7 15h10");
}

.f0eu_912v {
  fill: currentColor;
  d: path("M7 4h10v17H7Z");
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

.nzfvycb-k {
  d: path("M7 4h10v17H7Z");
}

.r182r524c {
  d: path("M7 9h10");
}

</style>
