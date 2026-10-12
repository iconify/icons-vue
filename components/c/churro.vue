<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o65he3bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:churro" /></template>
<style>
.o65he3bzw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.75 14.25l-3.6-9.5a1.625 1.625 0 0 1 3.25 0a1.625 1.625 0 0 1 3.25 0l3.6 9.5Zm3.25 0l-3.6-9.5m-.9 9.5h9q1.25 0 1.03 1.23l-.81 4.54q-.22 1.23-1.47 1.23h-6.5q-1.25 0-1.47-1.23l-.81-4.54q-.22-1.23 1.03-1.23");
}

</style>
