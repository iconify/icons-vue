<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k4gmqebhh"/><path class="lo970fxfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-at-risk" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k4gmqebhh {
  d: path("M4.75 2.5h9.5A1.75 1.75 0 0 1 16 4.25v15.5a1.75 1.75 0 0 1-1.75 1.75h-9.5A1.75 1.75 0 0 1 3 19.75V4.25A1.75 1.75 0 0 1 4.75 2.5");
}

.lo970fxfb {
  d: path("M8 21.5V17h3v4.5M7 7h.01M12 7h.01M7 11.5h.01m4.99 0h.01m6.99 3V18m0 3h.01");
}

</style>
