<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vym4iwb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-building-materials" /></template>
<style>
.vym4iwb4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.25 2.5h11V7h-11Zm0 7.25H7.5v4.5H2.25Zm8 0h11.5v4.5h-11.5Zm-8 7.25h11v4.5h-11ZM16 17h5.75v4.5H16Z");
}

</style>
