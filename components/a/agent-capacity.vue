<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo97qsbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:agent-capacity" /></template>
<style>
.wo97qsbsz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 9.25a6.75 6.75 0 0 1 13.5 0m-15.75 0H7v6H2.5Zm13.5 5.8v-5.8h4.5v5.7m-15.75.3v1.25a3 3 0 0 0 3 3h2.75m4.25 1.5a3.5 3.5 0 0 1 7 0m-3.5 0l2-2.75");
}

</style>
