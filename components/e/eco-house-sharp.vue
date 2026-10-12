<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x1mbz_b7o"/><path class="ijd22ib1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eco-house-sharp" /></template>
<style>
.ijd22ib1x {
  d: path("M8.75 18.25c.25-4.02 1.95-5.75 6.5-5.75c-.25 4.02-1.95 5.75-6.5 5.75Z");
}

.x1mbz_b7o {
  d: path("M3.25 19.75v-9l1.14-.98l6.47-5.54L12 3.25l1.14.98l6.47 5.54l1.14.98v10.5H3.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
