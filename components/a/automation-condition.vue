<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ldjmfpbrt"/><path class="n0v68cbqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:automation-condition" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldjmfpbrt {
  d: path("m10.058 5.558l.077-.933A1.5 1.5 0 0 1 11.63 3.25h.74a1.5 1.5 0 0 1 1.495 1.375l.077.933a1.5 1.5 0 0 0 .623 1.096l.45.321a1.5 1.5 0 0 0 1.543.121l.89-.445a1.5 1.5 0 0 1 1.992.63l.427.794a1.5 1.5 0 0 1-.46 1.94l-.767.537a1.5 1.5 0 0 0-.64 1.229v.438a1.5 1.5 0 0 0 .64 1.229l.767.537a1.5 1.5 0 0 1 .46 1.94l-.427.794a1.5 1.5 0 0 1-1.992.63l-.89-.445a1.5 1.5 0 0 0-1.543.121l-.45.321a1.5 1.5 0 0 0-.623 1.096l-.077.933a1.5 1.5 0 0 1-1.495 1.375h-.74a1.5 1.5 0 0 1-1.495-1.375l-.077-.933a1.5 1.5 0 0 0-.623-1.096l-.45-.321a1.5 1.5 0 0 0-1.543-.121l-.89.445a1.5 1.5 0 0 1-1.992-.63l-.427-.794a1.5 1.5 0 0 1 .46-1.94l.767-.537A1.5 1.5 0 0 0 6 12.219v-.438a1.5 1.5 0 0 0-.64-1.229l-.767-.537a1.5 1.5 0 0 1-.46-1.94l.427-.794a1.5 1.5 0 0 1 1.992-.63l.89.445a1.5 1.5 0 0 0 1.543-.121l.45-.321a1.5 1.5 0 0 0 .623-1.096");
}

.n0v68cbqh {
  d: path("M10 10a2 2 0 1 1 2 2v1m0 2.75h.01");
}

</style>
