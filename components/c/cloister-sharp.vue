<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmtijizwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cloister-sharp" /></template>
<style>
.mmtijizwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25V7L8.5 9.5V18v-1.75H5v5Zm18.5 0V7L15.5 9.5V18v-1.75H19v5ZM10.75 9.5h2.5V15h-2.5zM12 15v6.25");
}

</style>
