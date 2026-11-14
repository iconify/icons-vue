<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svz81kbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gift-shop" /></template>
<style>
.svz81kbma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3h15l2 5.5h-19ZM4 8.5v13h8.2m7.8-8.4V8.5M9.5 3l-.75 5.5M14.5 3l.75 5.5m-.25 9h6.5v4H15Zm3.25 0v4m0-4c-1.75-3-3.5-.75 0 0c3.5-.75 1.75-3 0 0");
}

</style>
