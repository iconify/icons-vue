<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="svwvd5b8p"/><path class="cd1qnjb2t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:field-type-date" /></template>
<style>
.cd1qnjb2t {
  d: path("M14 9.25h3.25A1.75 1.75 0 0 1 19 11v2.5a1.75 1.75 0 0 1-1.75 1.75H14a1.75 1.75 0 0 1-1.75-1.75V11A1.75 1.75 0 0 1 14 9.25m-1.75 2H19M14 8v2m3.25-2v2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.svwvd5b8p {
  d: path("M6 6h12a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 18 18H6a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 6 6m0 6h3.5");
}

</style>
