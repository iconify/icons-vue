<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ss_k9nbrc"/><path class="sh2e90bun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chromosome" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sh2e90bun {
  d: path("M16.5 3.5c-1.5 5.5-3 7-4.5 8.5s-3 3-4.5 8.5");
}

.ss_k9nbrc {
  d: path("M7.5 3.5c1.5 5.5 3 7 4.5 8.5s3 3 4.5 8.5");
}

</style>
