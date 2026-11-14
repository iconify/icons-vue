<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh4ndcfrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:alcohol-stove" /></template>
<style>
.sh4ndcfrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 12.5h15V16a3 3 0 0 1-3 3h-9a3 3 0 0 1-3-3Zm3 6.5v2.5m9-2.5v2.5M12 9.75a3 3 0 0 1-3-3c0-2 1.75-3 2.25-4.25C13.5 3.5 15 5 15 6.75a3 3 0 0 1-3 3");
}

</style>
