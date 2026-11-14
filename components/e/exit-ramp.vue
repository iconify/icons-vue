<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wwg0lprpc"/><path class="is2ghmbjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:exit-ramp" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.is2ghmbjm {
  d: path("M16.25 15h3.5a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 19.75 19h-3.5a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 16.25 15M18 19v2.5");
}

.wwg0lprpc {
  d: path("M2.5 2.5v19m6 0v-5c0-3.5 2.5-4.5 6-4.5h7m-13-9.5v3c0 2 2.5 3 6 3h7");
}

</style>
