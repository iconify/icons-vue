<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idux_w2pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ball-return" /></template>
<style>
.idux_w2pr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 9.5a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Zm9-3.25h.01m2.74 1.25h.01M13 9.25h.01M4.5 20h15M7 17.5L4.5 20L7 22");
}

</style>
