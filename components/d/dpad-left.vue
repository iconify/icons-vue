<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r8i9hobcb"/><path class="wp416ze0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dpad-left" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r8i9hobcb {
  d: path("M9.75 2.5h4.5A1.75 1.75 0 0 1 16 4.25v2A1.75 1.75 0 0 0 17.75 8h2a1.75 1.75 0 0 1 1.75 1.75v4.5A1.75 1.75 0 0 1 19.75 16h-2A1.75 1.75 0 0 0 16 17.75v2a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 19.75v-2A1.75 1.75 0 0 0 6.25 16h-2a1.75 1.75 0 0 1-1.75-1.75v-4.5A1.75 1.75 0 0 1 4.25 8h2A1.75 1.75 0 0 0 8 6.25v-2A1.75 1.75 0 0 1 9.75 2.5");
}

.wp416ze0n {
  d: path("M7.25 9.5L4.75 12l2.5 2.5");
}

</style>
