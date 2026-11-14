<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3y5ghmfv"/><path class="g8cscy_jg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anti-cheat" /></template>
<style>
.g8cscy_jg {
  d: path("M15.25 8.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m1.5 9h2.5A1.75 1.75 0 0 1 21 19.25v.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-.5a1.75 1.75 0 0 1 1.75-1.75m-.25 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r3y5ghmfv {
  d: path("M15.577 13H8l-.75 1c-.75 1-1.5 2-2.75 2s-2.25-1-2-3L3 9c.5-2.5 1.5-4.5 4-4.5h10c2.5 0 3.5 2 4 4.5l.5 4a4.3 4.3 0 0 1 .011 1.06M5.75 8.5h3.5M7.5 6.75v3.5");
}

</style>
