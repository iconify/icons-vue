<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg8yahbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:avatar-edit" /></template>
<style>
.gg8yahbqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 11.25a3.75 3.75 0 1 1 4.5 0c2.5 1 3.75 3.5 3.75 6.75v2a1 1 0 0 1-1 1h-10a1 1 0 0 1-1-1v-2c0-3.25 1.25-5.75 3.75-6.75Zm10.5 4.25l.5-2.25l3-3l1.5 1.5l-3 3Z");
}

</style>
