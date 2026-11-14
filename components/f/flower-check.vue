<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoef25bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flower-check" /></template>
<style>
.eoef25bmi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.25A2.5 2.5 0 1 1 13.25 10A2.5 2.5 0 1 1 10 12.5A2.5 2.5 0 1 1 6.75 10A2.5 2.5 0 1 1 8 6.25a2.5 2.5 0 1 1 4 0Zm-2 6.25v9M10 9h.01m4.74 9l2 2L21 15.75");
}

</style>
