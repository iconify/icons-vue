<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t015goc-r"/><path class="crgiq1byz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:biogas" /></template>
<style>
.crgiq1byz {
  d: path("M18.5 10c.5-3 1.5-4.5 3-5c.25 2.5-1 4.5-3 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t015goc-r {
  d: path("M3 19.5V11a5.5 5.5 0 0 1 11 0v8.5Zm11-6h4.5V10m0 0c-2.5-.5-3.5-3-3-5.5C18 5 19 7 18.5 10");
}

</style>
