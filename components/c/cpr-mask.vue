<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xbh5rhs5v"/><path class="ep2aj_p1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cpr-mask" /></template>
<style>
.ep2aj_p1l {
  fill: currentColor;
  d: path("M14.5 9.5c3-.5 4.25 1 4.25 2.5c0 1.75-1.75 2.5-4.25 2.25c-.5-1.5-.5-3.25 0-4.75m4 12s-3-2-3-3.75c0-1 .75-1.75 1.75-1.75c.5 0 1 .25 1.25.75c.25-.5.75-.75 1.25-.75c1 0 1.75.75 1.75 1.75c0 1.75-3 3.75-3 3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xbh5rhs5v {
  d: path("M6 19.5V16q-3-2.25-3-6c0-3.75 2.75-6.75 6.5-6.75c2.638 0 4.707 1.278 5.567 3.406m-2.504 9.594h-.313v3.25");
}

</style>
