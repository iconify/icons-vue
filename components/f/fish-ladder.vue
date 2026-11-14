<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w36r0rjmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fish-ladder" /></template>
<style>
.w36r0rjmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5h6v-4h6v-4h7m-3-6.5C16 3 10.5 3 8 7L4.5 4v6L8 7c2.5 4 8 4 10.5 0Zm-4-.25h.01");
}

</style>
