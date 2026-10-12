<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="a8dto-tab"/><path class="qpmal_ehx"/><path class="rhj7-w4rz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:food-processor-sharp" /></template>
<style>
.a8dto-tab {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6.25v-3.5h3.5v3.5m-6.75 9.5v-9.5h11.5v9.5Zm11.5-8h3.25v4h-3.25");
}

.qpmal_ehx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 11.75c1.5-1.75 3.25-1.5 3.25-.75s1.75 1 3.25-.75m-9.5 5.5h15.5v5.5H4.25z");
}

.rhj7-w4rz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
