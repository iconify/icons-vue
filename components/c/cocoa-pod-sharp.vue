<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="h_8qbsbuc"/><path class="gpevpk6iv"/><path class="q-ycj7bec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cocoa-pod-sharp" /></template>
<style>
.gpevpk6iv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.5 7.25l-.75 1.875V10.5m3.75-3.25l.75 1.875V10.5M5.5 12.25h13");
}

.h_8qbsbuc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 4l1.5-1.25M12 4c4.5 2 6.5 5.25 6.5 8.75s-2 6.5-6.5 8.5c-4.5-2-6.5-5-6.5-8.5S7.5 6 12 4Z");
}

.q-ycj7bec {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 15.5h.01m5.49 0h.01M12 18.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
