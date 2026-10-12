<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uwgkth96m"/><path class="dfcqmlbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bucket-list" /></template>
<style>
.dfcqmlbzj {
  d: path("M8.75 14.5L11 16.75l4.25-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uwgkth96m {
  d: path("M5.5 8.25c0-4.25 3-5.5 6.5-5.5s6.5 1.25 6.5 5.5m-12.75 0h12.5q1.5 0 1.27 1.48l-1.54 10.04q-.23 1.48-1.73 1.48h-8.5q-1.5 0-1.73-1.48L4.48 9.73q-.23-1.48 1.27-1.48");
}

</style>
