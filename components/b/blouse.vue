<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mi1rki3xk"/><path class="kodhyhbvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:blouse" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kodhyhbvj {
  d: path("M11.48 7.2L9.52 6.05q-.52-.3-.52.3v2.3q0 .6.52.3l1.96-1.15q.52-.3 0-.6m1.04 0l1.96-1.15q.52-.3.52.3v2.3q0 .6-.52.3L12.52 7.8q-.52-.3 0-.6m-1.27 1.3l-1 3.5m2.5-3.5l1 3.5");
}

.mi1rki3xk {
  d: path("M9.25 3.5h5.5q1 0 1.87.49l2.76 1.52q.87.49 1.02 1.48l.7 4.52q.15.99-.82 1.23l-1.06.27q-.97.24-1.23-.72l-.23-.83q-.26-.96-.24.04l.21 8.25q.02 1-.98 1h-9.5q-1 0-.98-1l.21-8.25q.02-1-.24-.04l-.23.83q-.26.96-1.23.72l-1.06-.27q-.97-.24-.82-1.23l.7-4.52Q3.75 6 4.62 5.51l2.76-1.52q.87-.49 1.87-.49");
}

</style>
