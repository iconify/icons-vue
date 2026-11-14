<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tmyes5nuj"/><path class="h4rwjacex"/><path class="fqc96sb6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-wreath" /></template>
<style>
.fqc96sb6e {
  d: path("m17 17.25l4.25-2.5Q21 19.5 17 17.25m1.5-4.75l1.25-4.75Q22.5 11 18.5 12.5M16.25 8l-2.5-4.25q4.25.5 2.5 4.25");
}

.h4rwjacex {
  d: path("M9.75 19a6.5 6.5 0 0 0 6.5-11M7 17.25l-4.25-2.5Q3 19.5 7 17.25M5.5 12.5L4.25 7.75Q1.5 11 5.5 12.5M7.75 8l2.5-4.25Q6 4.25 7.75 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tmyes5nuj {
  d: path("M14.25 19a6.5 6.5 0 0 1-6.5-11");
}

</style>
