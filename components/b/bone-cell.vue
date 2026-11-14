<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o1z2wccdo"/><path class="i9qc87h4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bone-cell" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i9qc87h4h {
  d: path("m15.5 8.5l2.25-2.25h2.75m-2.75 0V3.5m-9.25 5L6.25 6.25H3.5m2.75 0V3.5m9.25 12l2.25 2.25h2.75m-2.75 0v2.75m-9.25-5l-2.25 2.25H3.5m2.75 0v2.75M12 12h.01");
}

.o1z2wccdo {
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

</style>
