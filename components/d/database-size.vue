<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xf_pdwqmz"/><path class="o09hoeuyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:database-size" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o09hoeuyk {
  d: path("M3 5.5C3 7 5.7 8.25 9 8.25S15 7 15 5.5M3 12c0 1.5 2.7 2.75 6 2.75s6-1.25 6-2.75m4.75-9v18M18 4.75L19.75 3l1.75 1.75M18 19.25L19.75 21l1.75-1.75");
}

.xf_pdwqmz {
  d: path("M3 5.5C3 4 5.7 2.75 9 2.75S15 4 15 5.5v13c0 1.5-2.7 2.75-6 2.75S3 20 3 18.5Z");
}

</style>
