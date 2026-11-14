<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eegkj9bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:duckweed" /></template>
<style>
.eegkj9bsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12q3-3.5 6 0q-3 3.5-6 0Zm6-4q3-3.5 6 0q-3 3.5-6 0Zm6 4q3-3.5 6 0q-3 3.5-6 0ZM2.5 17.5q2.25-1.5 4.75 0t4.75 0t4.75 0t4.75 0");
}

</style>
