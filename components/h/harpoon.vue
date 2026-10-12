<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8e9mhgew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:harpoon" /></template>
<style>
.e8e9mhgew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 18.5L16 8m5.03-4.8l-3.06 6.35q-.22.45-.47.01l-.85-1.52q-.25-.44-.69-.69l-1.52-.85q-.44-.25.01-.47l6.35-3.06q.45-.22.23.23M5.5 18.5c-2.25.25-3.25-2.5-1.5-3.75s3.5.25 2.75 1.75m-1.25 2l1.75 2.75");
}

</style>
