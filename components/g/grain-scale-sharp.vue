<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fmutlwbth"/><path class="v6fz7nsrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grain-scale-sharp" /></template>
<style>
.fmutlwbth {
  d: path("M6 8.25c1-3 3.25-4.75 6-4.75s5 1.75 6 4.75Zm-2.25 0h16.5m-8.25 0v2.5m-6 0h13l.14.99l1.22 8.52l.14.99h-17l.14-.99l1.22-8.52l.14-.99z");
}

.v6fz7nsrp {
  d: path("M9.25 16a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M12 16l1.25-1.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
