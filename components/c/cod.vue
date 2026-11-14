<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlip9ofwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cod" /></template>
<style>
.xlip9ofwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12c2-5 7-5.5 12-3.5l5.5-3L19 12l1.5 6.5l-5.5-3C10 17.5 5 17 3 12Zm1.5 2.5V18m2.75-7.25h.01");
}

</style>
