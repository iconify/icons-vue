<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z62afx4kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:analytics-insight-sharp" /></template>
<style>
.z62afx4kb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75a6.75 6.75 0 0 0-4 12.2V18h8v-3.05a6.75 6.75 0 0 0-4-12.2Zm-2.25 18.5h4.5m-4.75-9v-1.5m2.5 1.5v-4.5m2.5 4.5V9.5");
}

</style>
