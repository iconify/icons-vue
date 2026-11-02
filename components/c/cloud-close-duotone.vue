<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d06hhzb4e"/><path class="m-5tw2b-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-close-duotone" /></template>
<style>
.d06hhzb4e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6.26 8.045C6.794 6.596 7.715 5.283 9 4.408a6.17 6.17 0 0 1 4.398-1.022a6 6 0 0 1 2.151.755c2.147 1.246 3.217 3.547 3.415 5.951A5.002 5.002 0 0 1 18 20H7a6 6 0 0 1-.74-11.955");
}

.ft5dv1b6b {
  fill: none;
}

.m-5tw2b-m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19A5 5 0 0 1 7 9c2-7 11-6 11 2a4 4 0 1 1 0 8Zm3-8l4 4m0-4l-4 4");
}

</style>
