<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xlc571slo"/><path class="tbm346t9w"/><path class="g6y9kqbow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fire-season" /></template>
<style>
.g6y9kqbow {
  d: path("M9.75 16.5c0-1.25 1.25-2 2-2.75c1.25.75 2.5 1.5 2.5 2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tbm346t9w {
  d: path("M12 18.75c-3.25 0-5.25-2-5.25-4.75c0-3 2.75-4.5 3.75-6.75C12 8.25 13 9.5 13.25 11c.75-.5 1.25-1.25 1.5-2c1.5 1.5 2.5 3 2.5 5c0 2.75-2 4.75-5.25 4.75");
}

.xlc571slo {
  d: path("M6.5 4h11A3.5 3.5 0 0 1 21 7.5V18a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 18V7.5A3.5 3.5 0 0 1 6.5 4M8 2.5V6m8-3.5V6");
}

</style>
