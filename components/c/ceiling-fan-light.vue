<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjgzpjbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ceiling-fan-light" /></template>
<style>
.wjgzpjbej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 4.5h5m-2.5 0v6m-2.5 0h5v3h-5Zm-7 1.5h7m5 0h7M12 13.5V16m-4 0h8a4 4 0 0 1-8 0Z");
}

</style>
