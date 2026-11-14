<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fukhy7_vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:branding-iron" /></template>
<style>
.fukhy7_vo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.391 19.737l4.596-4.596l2.122 2.122l-4.596 4.596ZM8.25 16l7.5-7.5m-.548-6.523l7.071 7.071l-2.475 2.475l-7.071-7.071Z");
}

</style>
