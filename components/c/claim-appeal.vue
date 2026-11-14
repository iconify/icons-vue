<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uwivq1yig"/><path class="b6m3xgj2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:claim-appeal" /></template>
<style>
.b6m3xgj2k {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4m-7.5 2v8m-3 0h6M8 12h8m-8 0l-1.25 3a1.25 1.25 0 0 0 2.5 0Zm8 0l-1.25 3a1.25 1.25 0 0 0 2.5 0Z");
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

</style>
