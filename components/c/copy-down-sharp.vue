<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sbuzb78qh"/><path class="flmsr_bnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:copy-down-sharp" /></template>
<style>
.flmsr_bnl {
  d: path("M15.25 8.75v-6H2.75v12.5h6");
}

.sbuzb78qh {
  d: path("M8.75 8.75h12.5v12.5H8.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
