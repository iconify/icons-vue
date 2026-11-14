<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6nu4lk3f"/><path class="ml65fie1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:foreclosure" /></template>
<style>
.e6nu4lk3f {
  d: path("M3.945 9.713L10.32 4.4a2.625 2.625 0 0 1 3.36 0l6.375 5.313A2.63 2.63 0 0 1 21 11.729v6.646A2.625 2.625 0 0 1 18.375 21H5.625A2.625 2.625 0 0 1 3 18.375v-6.646a2.63 2.63 0 0 1 .945-2.016");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ml65fie1m {
  d: path("M9.75 14h4.5A1.75 1.75 0 0 1 16 15.75v3.5A1.75 1.75 0 0 1 14.25 21h-4.5A1.75 1.75 0 0 1 8 19.25v-3.5A1.75 1.75 0 0 1 9.75 14m0 0v-1.5a2.25 2.25 0 0 1 4.5 0V14M12 17.5h.01");
}

</style>
