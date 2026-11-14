<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcs2lkbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ac-dry-mode" /></template>
<style>
.pcs2lkbck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h19v8h-19ZM6 8h12m-6 6s-3 3-3 4.5a3 3 0 0 0 6 0c0-1.5-3-4.5-3-4.5Z");
}

</style>
