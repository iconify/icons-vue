<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qdt43xbdg"/><path class="ev_ssibxk"/><path class="nz45umbbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:foot" /></template>
<style>
.ev_ssibxk {
  fill: currentColor;
  d: path("M7.5 4.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m4-1.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m2.75.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m2.5 1.5a.5.5 0 1 0 1 0a.5.5 0 1 0-1 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nz45umbbi {
  d: path("M18.5 7.5h.01");
}

.qdt43xbdg {
  d: path("M9.5 9.25c3.5-1 6.75-.25 7 3c.25 2.75-1.25 4.5-1.5 6.5c-.25 1.75-1.5 2.75-3.25 2.5c-2-.25-2.75-1.5-3-3.25C8.5 15.5 7 14 7 12c0-1.5 1-2.5 2.5-2.75");
}

</style>
