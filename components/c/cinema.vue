<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fddi1jbma"/><circle class="g5fitnk0m"/><circle class="bed10cc0g"/><path class="xnz-8khsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:cinema" /></template>
<style>
.bed10cc0g {
  cx: 42px;
  cy: 24px;
  r: 3px;
  fill: currentColor;
}

.fddi1jbma {
  fill: currentColor;
  d: path("M35 27.869A8 8 0 0 1 28 32h14a8 8 0 0 1-7-4.131");
}

.g5fitnk0m {
  cx: 28px;
  cy: 24px;
  r: 3px;
  fill: currentColor;
}

.xnz-8khsk {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m14 30c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H23c-1.1 0-2-.9-2-2v-.5L16 48V32l5 2.5V34c0-1.1.9-2 2-2h5a8 8 0 0 1 0-16a8 8 0 0 1 7 4.131A8 8 0 0 1 42 16a8 8 0 0 1 0 16z");
}

</style>
