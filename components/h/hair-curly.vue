<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuakx0b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hair-curly" /></template>
<style>
.zuakx0b9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3.5c3 0 3.25 4.25.25 4.25c-1.5 0-1.5-2 0-1.75c3.25.75 3 5.75 0 5.75c-1.5 0-1.5-2 0-1.75c3.25.75 3 5.75 0 5.75c-1.5 0-1.5-2 0-1.75c3.25.75 3 6.5-.25 6.5m8-17c3 0 3.25 4.25.25 4.25c-1.5 0-1.5-2 0-1.75c3.25.75 3 5.75 0 5.75c-1.5 0-1.5-2 0-1.75c3.25.75 3 5.75 0 5.75c-1.5 0-1.5-2 0-1.75c3.25.75 3 6.5-.25 6.5");
}

</style>
