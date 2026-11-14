<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng1o5ybam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:colloid" /></template>
<style>
.ng1o5ybam {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c-3 4-7 8-7 12a7 7 0 0 0 14 0c0-4-4-8-7-12Zm0 7.5h.01M9 14.5h.01m5.99 0h.01M12 18h.01");
}

</style>
