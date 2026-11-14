<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyzpsd06c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:business-legal-expenses" /></template>
<style>
.eyzpsd06c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5v17m-6 0h12M4.5 7h15m-15 0l-2 6a2.5 2.5 0 0 0 4 0Zm15 0l-2 6a2.5 2.5 0 0 0 4 0Z");
}

</style>
