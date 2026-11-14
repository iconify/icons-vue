<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q7ce0obic"/><path class="feh94fb1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lymphatic-system" /></template>
<style>
.feh94fb1h {
  d: path("M8.5 8.5c0 2.5 7-2 7 .5m0 6c0 2.5-7-2-7 .5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q7ce0obic {
  d: path("M6 5.5a2.5 3 0 1 0 5 0a2.5 3 0 1 0-5 0m7 6.5a2.5 3 0 1 0 5 0a2.5 3 0 1 0-5 0m-7 6.5a2.5 3 0 1 0 5 0a2.5 3 0 1 0-5 0");
}

</style>
