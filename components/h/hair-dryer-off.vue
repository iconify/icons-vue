<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixfrsi84o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hair-dryer-off" /></template>
<style>
.ixfrsi84o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4h7l2 1.5v5L14 12H7a4 4 0 0 1 0-8Zm-.5 8H10v8.5H6.5Zm9.5 4a3 3 0 1 0 4.5 0m-2.25-2v3.5");
}

</style>
