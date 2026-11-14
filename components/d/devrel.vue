<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iow279dbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:devrel" /></template>
<style>
.iow279dbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM2.5 21c0-3.75 2.25-6 5-6s5 2.25 5 6M14 7.25h2L21.5 4v10L16 10.75h-2Z");
}

</style>
