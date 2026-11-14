<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="orwd-jzrd"/><path class="worjjwb5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:laundry-hamper" /></template>
<style>
.orwd-jzrd {
  d: path("M4.5 10h15L18 19.5a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 19.5Zm15 0L7 4m6.25 3l-1-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.worjjwb5n {
  d: path("M7 10v4a1.5 1.5 0 0 0 3 0v-4m2.75 3v4m2.75-4v4");
}

</style>
