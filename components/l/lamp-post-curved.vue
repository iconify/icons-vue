<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e08sp0b6y"/><path class="mkp-21kph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lamp-post-curved" /></template>
<style>
.e08sp0b6y {
  d: path("M5 21.5h6m-3 0V8c0-3 2-4.5 5-4.5h3.5V5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mkp-21kph {
  d: path("M13 8.5Q13 5 16.5 5T20 8.5Z");
}

</style>
