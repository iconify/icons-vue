<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xujbo5oql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:feels-like-hot" /></template>
<style>
.xujbo5oql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 13.5v-8a3 3 0 0 1 6 0v8a4.5 4.5 0 1 1-6 0Zm3-6.5v9.75m8.5-11.25L20 8.75a2.75 2.75 0 1 1-4.5 0Z");
}

</style>
