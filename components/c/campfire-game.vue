<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt1jk4kca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:campfire-game" /></template>
<style>
.tt1jk4kca {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5Q16.5 7 16.5 10a4.5 4.5 0 0 1-9 0q0-3 4.5-7.5Zm-8 18l16-5m-16 0l16 5");
}

</style>
