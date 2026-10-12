<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g_qimlbtd"/><path class="w8qktbmwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bottle-opener" /></template>
<style>
.g_qimlbtd {
  d: path("M10 12.33v6.92a2 2 0 0 0 4 0v-6.92a5 5 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w8qktbmwb {
  d: path("M9.5 6.5h5a2.5 2.5 0 0 1-5 0");
}

</style>
