<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghlt1cbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forest-edge" /></template>
<style>
.ghlt1cbkl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14L4.75 3L7 14l2.5-9l2.5 9l2-6l2 6Zm0 5h19M4.75 14v5m4.75-5v5m4.5-5v5");
}

</style>
