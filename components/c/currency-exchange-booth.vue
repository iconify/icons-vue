<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t9pjwudpi"/><path class="dqftgcc5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:currency-exchange-booth" /></template>
<style>
.dqftgcc5e {
  d: path("M8 9h3.5a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5H8a1.5 1.5 0 0 1-1.5-1.5v-2A1.5 1.5 0 0 1 8 9m-2.5 6.75h6.2m2.8.25h7m-1.75-1.75L21.5 16l-1.75 1.75M21.5 20h-7m1.75-1.75L14.5 20l1.75 1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t9pjwudpi {
  d: path("M4.25 2.5h15.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75H4.25A1.75 1.75 0 0 1 2.5 4.75v-.5A1.75 1.75 0 0 1 4.25 2.5M4 6.5v15h8.1m7.9-10v-5");
}

</style>
