<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t94ur7mtj"/><path class="n0atc7bic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-radar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0atc7bic {
  d: path("m12.53 6.78l2.62 2.57q.53.53.69 1.26l.76 3.41q.16.73-.57.88l-3.3.7q-.73.15-1.46-.03l-3.09-.76q-.73-.18-.48-.89l1.02-2.96q.25-.71.7-1.31l2.13-2.8q.45-.6.98-.07");
}

.t94ur7mtj {
  d: path("m13.3 3.5l5.41 3.13q1.3.75 1.3 2.25v6.25q0 1.5-1.3 2.25L13.3 20.5q-1.3.75-2.6 0l-5.41-3.12q-1.3-.75-1.3-2.25V8.87q0-1.5 1.3-2.25L10.7 3.5q1.3-.75 2.6 0");
}

</style>
