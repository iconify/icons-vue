<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ep4yrs5sy"/><path class="i9rul54th"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:course-sharp" /></template>
<style>
.ep4yrs5sy {
  d: path("M4.25 4.25h15.5v11H4.25zM2.75 19h18.5");
}

.i9rul54th {
  d: path("m12.45 6.46l3.35 1.58l.45.21l-.45.21l-3.35 1.58l-.45.21l-.45-.21L8.2 8.46l-.45-.21l.45-.21l3.35-1.58l.45-.21zm-2.7 4.04V12L12 13.5l2.25-1.5v-1.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
