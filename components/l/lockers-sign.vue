<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oeirtxgkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lockers-sign" /></template>
<style>
.oeirtxgkm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5h17v19h-17Zm8.5 0v19M6.25 5.25h3M6.25 8h3m5.5-2.75h3m-3 2.75h3m-8.5 4.5V15m5.5-2.5V15");
}

</style>
