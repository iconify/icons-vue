<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v03kfabiw"/><path class="ya1yarb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-boiler-cover" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v03kfabiw {
  d: path("M9.875 3.5h4.25A4.375 4.375 0 0 1 18.5 7.875v8.25a4.375 4.375 0 0 1-4.375 4.375h-4.25A4.375 4.375 0 0 1 5.5 16.125v-8.25A4.375 4.375 0 0 1 9.875 3.5");
}

.ya1yarb3w {
  d: path("M10.5 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M12 18c-1.75 0-3-1.1-3-2.5c0-1.75 2-2.5 2.25-4c1 .75 1.25 1.5 1.25 2.5c1-.5 1.5-1.25 1.75-2c.5 1 .75 2 .75 3.5c0 1.4-1.25 2.5-3 2.5");
}

</style>
