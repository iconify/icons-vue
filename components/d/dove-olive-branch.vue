<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z9p9s4xlu"/><path class="hiyifviqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dove-olive-branch" /></template>
<style>
.hiyifviqt {
  d: path("M20.5 8.5q-2.5-.5-3-3q2.5.25 3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z9p9s4xlu {
  d: path("M2.5 17L7 14.5l-2-10l7.5 6.5c.5-2.5 4-3 4.5-.5l2 1l-2.5 1c-1 3.5-5 5.5-9.5 4ZM19 11.5Q21 9 21.5 5");
}

</style>
