<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g9msq0hph"/><path class="ab-94pb1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hangar" /></template>
<style>
.ab-94pb1j {
  d: path("M6.5 20.5v-8h11v8");
}

.g9msq0hph {
  d: path("M2.5 20.5V11a9.5 8 0 0 1 19 0v9.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
