<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llna05bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ceiling-fan-sharp" /></template>
<style>
.llna05bzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v4.5m-2 0h5.5V9h5.75v2.5H15.5v1.75h-7V11.5H2.75V9H8.5V7.25zm-1 8.5h6a3 3 0 0 1-6 0Z");
}

</style>
