<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zp8xm8b8l"/><path class="i00z5fbcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ethical-sourcing-tag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i00z5fbcz {
  d: path("M6.25 7.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m2.5 5l2.75 2.75l4-4");
}

.zp8xm8b8l {
  d: path("M6.125 3.5h4.288a2.63 2.63 0 0 1 1.856.769l6.375 6.375a2.625 2.625 0 0 1 0 3.712l-4.288 4.288a2.625 2.625 0 0 1-3.712 0l-6.375-6.375a2.63 2.63 0 0 1-.769-1.856V6.125A2.625 2.625 0 0 1 6.125 3.5");
}

</style>
