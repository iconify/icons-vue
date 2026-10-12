<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrh66oqyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:darkroom-light-sharp" /></template>
<style>
.mrh66oqyj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75V7M9.75 7h5.75l.62 1.09l3.01 5.32l.62 1.09H4.25l.62-1.09l3.01-5.32L8.5 7zM9 14.5a3 3 0 0 0 6 0Zm3 5v1.75m-3.36-3.39l-1.41 1.41m8.13-1.41l1.41 1.41");
}

</style>
