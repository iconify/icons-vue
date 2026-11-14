<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi3p_abdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dream-journal" /></template>
<style>
.bi3p_abdd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 13.5c-2-1.5-5.5-2-9-1.5v8c3.5-.5 7 0 9 1.5c2-1.5 5.5-2 9-1.5v-8c-3.5-.5-7 0-9 1.5Zm0 0v8M13.75 3a3.75 3.75 0 1 0 1.5 5a3 3 0 0 1-1.5-5Z");
}

</style>
