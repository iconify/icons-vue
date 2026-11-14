<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn5zjyfrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:field-hockey-ball" /></template>
<style>
.hn5zjyfrh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0Zm7-3h.01m-3.01 3h.01m5.99 0h.01m-3.01 3h.01M2.5 9H5m-2.5 6H5");
}

</style>
