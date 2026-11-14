<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6b0iky2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coverage-limit" /></template>
<style>
.o6b0iky2o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13C2.5 8 7 5 12 5s9.5 3 9.5 8c-1.5-1-2.75-1-4.25 0c-1.5-1-3-1-5.25 0c-2.25-1-3.75-1-5.25 0c-1.5-1-2.75-1-4.25 0Zm9.5 0v6c0 1.4-1 2.5-2.25 2.5s-2-1-2-2M5 2.5h14");
}

</style>
