<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mdjg7jbex"/><path class="lft9d5bss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:house-wifi" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lft9d5bss {
  d: path("M10 21.5v-4h4v4M9.879 6.879a3 3 0 0 1 4.242 0M7.404 4.404a6.5 6.5 0 0 1 9.192 0");
}

.mdjg7jbex {
  d: path("m5.279 13.48l5.75-3.833a1.75 1.75 0 0 1 1.942 0l5.75 3.833a1.75 1.75 0 0 1 .779 1.457v4.813a1.75 1.75 0 0 1-1.75 1.75H6.25a1.75 1.75 0 0 1-1.75-1.75v-4.813a1.75 1.75 0 0 1 .779-1.457");
}

</style>
