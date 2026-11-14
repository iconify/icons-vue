<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzuca5bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:capital-city" /></template>
<style>
.gzuca5bwr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.25L12.5 4h2L13 5l.5 1.75l-1.5-1l-1.5 1L11 5L9.5 4h2Zm0 3.5V8m-4.5 4.5a4.5 4.5 0 0 1 9 0m-13 0h17m-17 9h17M7 12.5v9m5-9v9m5-9v9");
}

</style>
