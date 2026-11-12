<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jpo7_pb2a"/><path class="oy1zyc70h"/><path class="sflfg-b2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-bottom-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jpo7_pb2a {
  d: path("M2 21L22 21");
}

.oy1zyc70h {
  d: path("M10 14.5L10 5.5C10 4.56538 10 4.09808 9.79904 3.75C9.66739 3.52197 9.47803 3.33261 9.25 3.20096C8.90192 3 8.43462 3 7.5 3C6.56538 3 6.09808 3 5.75 3.20096C5.52197 3.33261 5.33261 3.52197 5.20096 3.75C5 4.09808 5 4.56538 5 5.5L5 14.5C5 15.4346 5 15.9019 5.20096 16.25C5.33261 16.478 5.52197 16.6674 5.75 16.799C6.09808 17 6.56538 17 7.5 17C8.43462 17 8.90192 17 9.25 16.799C9.47803 16.6674 9.66739 16.478 9.79904 16.25C10 15.9019 10 15.4346 10 14.5Z");
}

.sflfg-b2u {
  d: path("M19 14.5L19 8.5C19 7.56538 19 7.09808 18.799 6.75C18.6674 6.52197 18.478 6.33261 18.25 6.20096C17.9019 6 17.4346 6 16.5 6C15.5654 6 15.0981 6 14.75 6.20096C14.522 6.33261 14.3326 6.52197 14.201 6.75C14 7.09808 14 7.56538 14 8.5L14 14.5C14 15.4346 14 15.9019 14.201 16.25C14.3326 16.478 14.522 16.6674 14.75 16.799C15.0981 17 15.5654 17 16.5 17C17.4346 17 17.9019 17 18.25 16.799C18.478 16.6674 18.6674 16.478 18.799 16.25C19 15.9019 19 15.4346 19 14.5Z");
}

</style>
