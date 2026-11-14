<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgtiahbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:almonds" /></template>
<style>
.zgtiahbgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c3.25 2.25 3.75 5.5 3.25 7c-.75 2-5.75 2-6.5 0c-.5-1.5 0-4.75 3.25-7ZM2.5 17C5 13.75 8 13.25 9.25 13.75c1.75.75 1.75 5.75 0 6.5C8 20.75 5 20.25 2.5 17Zm19 0c-2.5-3.25-5.5-3.75-6.75-3.25c-1.75.75-1.75 5.75 0 6.5c1.25.5 4.25 0 6.75-3.25ZM12 5.5v3.25");
}

</style>
