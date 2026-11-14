<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqaxxebse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:board-filter" /></template>
<style>
.jqaxxebse {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3h4v17h-4Zm6.75 9.2V3h4v9.2M16.25 3h4v7h-4Zm-1.5 12h6.5l-2.5 3v3.25l-1.5-.75V18Z");
}

</style>
