<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufrlo7bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cupcake" /></template>
<style>
.ufrlo7bbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 12.5h12l-1.25 8h-9.5Zm-1.25 0c-1 0-1.5-.75-1.25-1.75C4.25 7.25 7.75 5 12 5s7.75 2.25 8.5 5.75c.25 1-.25 1.75-1.25 1.75Zm5.25 0l.5 8m3.5-8l-.5 8M12 2.5h.01");
}

</style>
