<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cos8znbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fossil-dig-kit" /></template>
<style>
.cos8znbuw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 14.5L14.5 7a2.4 2.4 0 1 1 3.75-1.25A2.4 2.4 0 1 1 17 9.5L9.5 17a2.4 2.4 0 1 1-3.75 1.25A2.4 2.4 0 1 1 7 14.5Zm8.5 2.5h6c0 2.5-1.5 4-3 5c-1.5-1-3-2.5-3-5Zm3-3.25V17");
}

</style>
