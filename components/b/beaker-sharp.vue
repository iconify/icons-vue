<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_tue2z5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:beaker-sharp" /></template>
<style>
.s_tue2z5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.75h14.5V14h-13V5.5ZM5.75 14h13v7.25h-13v-2.5Zm10-7.5h-2.5m2.5 3.5h-2.5");
}

</style>
