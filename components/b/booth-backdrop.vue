<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7e8r8buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:booth-backdrop" /></template>
<style>
.f7e8r8buw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19l-1.5 2l1.5 2h-19l1.5-2Zm2 4h15v11h-15Zm2.5 11V21m10-3.5V21M5 21h4m6 0h4");
}

</style>
