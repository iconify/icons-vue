<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tuk3-wb0h"/><path class="v8wsbjbnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bouquet-toss" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tuk3-wb0h {
  d: path("M10.75 5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m5.5 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

.v8wsbjbnk {
  d: path("M13.5 9.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m.75 2l-4.5 4.5m0 0l-3-1.5L8 13.25Zm0 0C8 18 6 18.75 3.5 18.5m6.25-2.25c-1 2-1.5 3.5-1.25 5.25m5-1q5-.5 7.5-5m-7 1.25q3-.25 4.5-2.25");
}

</style>
