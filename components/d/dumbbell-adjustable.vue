<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yymr5sbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dumbbell-adjustable" /></template>
<style>
.yymr5sbbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3H7v9.5H2.5Zm12.7 9.5h-.7V3H19v8.8M7 7.75h7.5m3.5 7v7m-2-5l2-2l2 2m-4 3l2 2l2-2");
}

</style>
