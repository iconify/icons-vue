<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p97i157qv"/><path class="p8dwfybut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:audit-sample-pick" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p8dwfybut {
  d: path("m5 6.75l1.5 1.5L8.75 5.5m6.75 11.75l1.5 1.5L19.25 16");
}

.p97i157qv {
  d: path("M5.625 3h2.25A2.625 2.625 0 0 1 10.5 5.625v2.25A2.625 2.625 0 0 1 7.875 10.5h-2.25A2.625 2.625 0 0 1 3 7.875v-2.25A2.625 2.625 0 0 1 5.625 3m10.5 0h2.25A2.625 2.625 0 0 1 21 5.625v2.25a2.625 2.625 0 0 1-2.625 2.625h-2.25A2.625 2.625 0 0 1 13.5 7.875v-2.25A2.625 2.625 0 0 1 16.125 3m-10.5 10.5h2.25a2.625 2.625 0 0 1 2.625 2.625v2.25A2.625 2.625 0 0 1 7.875 21h-2.25A2.625 2.625 0 0 1 3 18.375v-2.25A2.625 2.625 0 0 1 5.625 13.5m10.5 0h2.25A2.625 2.625 0 0 1 21 16.125v2.25A2.625 2.625 0 0 1 18.375 21h-2.25a2.625 2.625 0 0 1-2.625-2.625v-2.25a2.625 2.625 0 0 1 2.625-2.625");
}

</style>
