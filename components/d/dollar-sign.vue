<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm4o5_btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dollar-sign" /></template>
<style>
.rm4o5_btl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 7.5C16 5.8 14.3 5 12 5C9.3 5 7.5 6.3 7.5 8.25c0 4.75 9 2.25 9 7.25c0 2.1-1.9 3.5-4.5 3.5c-2.4 0-4.2-.9-4.75-2.5M12 2.5V5m0 14v2.5");
}

</style>
