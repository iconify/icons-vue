<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8fqigb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cinnamon-roll" /></template>
<style>
.q8fqigb0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3a9 9 0 0 1 0 18a7.5 7.5 0 0 1 0-15a6 6 0 0 1 0 12a4.5 4.5 0 0 1 0-9a3 3 0 0 1 0 6");
}

</style>
