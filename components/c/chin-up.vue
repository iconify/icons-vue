<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko9ot6bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chin-up" /></template>
<style>
.ko9ot6bkl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.5h19M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-2.5 6l2 5h7l2-5m-8 5v5m5-5v5");
}

</style>
