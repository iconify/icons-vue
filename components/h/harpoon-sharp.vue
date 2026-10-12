<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0b7403wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:harpoon-sharp" /></template>
<style>
.a0b7403wp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 18.5L16 8m5.03-4.8l-3.06 6.35l-.22.45l-.25-.44l-.85-1.52l-.25-.44l-.44-.25l-1.52-.85l-.44-.25l.45-.22l6.35-3.06l.45-.22zM5.5 18.5c-2.25.25-3.25-2.5-1.5-3.75s3.5.25 2.75 1.75m-1.25 2l1.75 2.75");
}

</style>
