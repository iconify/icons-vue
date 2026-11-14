<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="msxyrx-ob"/><path class="tjhblnbfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ethical-hacker" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.msxyrx-ob {
  d: path("M4 21.5v-2c0-2 1.5-3 3-3.5c-1.25-2-1.75-4.5-1.25-7C6.5 6 9.5 3.5 12 2.5c2.5 1 5.5 3.5 6.25 6.5a9.66 9.66 0 0 1-1.036 6.639M20 20.704v.796");
}

.tjhblnbfe {
  d: path("M9 11.5a3 3.75 0 1 0 6 0a3 3.75 0 1 0-6 0m5.75 6.5l2 2L21 15.75");
}

</style>
