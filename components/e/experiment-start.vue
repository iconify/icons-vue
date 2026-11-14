<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbax_44cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:experiment-start" /></template>
<style>
.sbax_44cj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.216 21H2.5l6-12V2.5H13V9l.805 1.61M6.5 13h5.7m2.8 1.5l6 3.5l-6 3.5Z");
}

</style>
