<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fnpznjxhp"/><path class="s47k4abef"/><path class="kuhn_7bnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-historian" /></template>
<style>
.fnpznjxhp {
  d: path("M11.79 21.249C7.486 21.21 4 19.976 4 18.5v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v7.355");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kuhn_7bnb {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.2 2.3 2.2 5.5 2.5m5 6l2-3l2 1.5l2.5-3.5");
}

.s47k4abef {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75s8-1.25 8-2.75");
}

</style>
