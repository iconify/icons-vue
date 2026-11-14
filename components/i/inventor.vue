<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byan2mbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:inventor" /></template>
<style>
.byan2mbcj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 17.75c0-2-2.5-3-2.5-5.75a4.75 4.75 0 0 1 9.5 0c0 2.75-2.5 3.75-2.5 5.75Zm.25 3h4M12 2.5v2m-6.75.75l1.5 1.5m12-1.5l-1.5 1.5");
}

</style>
