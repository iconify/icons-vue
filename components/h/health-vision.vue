<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlq-tacxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-vision" /></template>
<style>
.rlq-tacxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 14a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm11 0a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm-3.5 0h3.5m-11-1l.75-5m17.75 5l-.75-5");
}

</style>
