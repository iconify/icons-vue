<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy_uxeb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:journal-entry" /></template>
<style>
.dy_uxeb3m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21 11.028V3.5c-3.5-.5-7 0-9 1.5c-2-1.5-5.5-2-9-1.5V18c3.437-.491 6.874-.018 8.89 1.42M12 5v14.2m2.25 2.3l.75-2.75l4.5-4.5a1.4 1.4 0 0 1 2 2l-4.5 4.5Z");
}

</style>
