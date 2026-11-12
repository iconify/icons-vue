<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i4anzi58i"/><path class="qo_q4hblb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevron-first-linear" /></template>
<style>
.i4anzi58i {
  stroke-linejoin: round;
  d: path("M16.5 19L10.5 12L16.5 5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qo_q4hblb {
  d: path("M7.49998 5L7.49996 19.0004");
}

</style>
