<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohjglfbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hanger-plus-sharp" /></template>
<style>
.ohjglfbeq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 6.75A2.25 2.25 0 1 1 12 9v1.75m0 0l8.1 6.3a1.5 1.5 0 0 1-.92 2.7H4.82a1.5 1.5 0 0 1-.92-2.7Z");
}

</style>
