<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uwivq1yig"/><path class="c0rne7bvi"/><path class="vjcqfytci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:file-sql" /></template>
<style>
.c0rne7bvi {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M8.25 12.75a3.75 1.5 0 1 0 7.5 0a3.75 1.5 0 1 0-7.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uwivq1yig {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5Z");
}

.vjcqfytci {
  d: path("M8.25 12.75v4.5a3.75 1.5 0 0 0 7.5 0v-4.5");
}

</style>
