<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bem5_qf8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:group-selfie" /></template>
<style>
.bem5_qf8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 10a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM6.5 21.5C6.5 17.75 9 16 12 16s5.5 1.75 5.5 5.5M7 18.5l-2.5-9m-2-7h4v7h-4Zm14.5 4a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm.25 7c.25-1.5 1-2.25 2-2.25c1.25 0 2.25 1 2.25 2.25");
}

</style>
