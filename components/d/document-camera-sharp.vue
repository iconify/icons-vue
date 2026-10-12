<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h58hk8bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:document-camera-sharp" /></template>
<style>
.h58hk8bdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 18.25h7v3h-7zm3.5 0V5h7m0-2.25h8v4.5h-8zm-1.5 9h9.5v9.5h-9.5z");
}

</style>
