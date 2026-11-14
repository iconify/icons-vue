<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxsd6eywu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:abv-mark" /></template>
<style>
.qxsd6eywu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5h4v4c0 1.5 3.5 2 3.5 4.5v9a1.5 1.5 0 0 1-1.5 1.5H8A1.5 1.5 0 0 1 6.5 20v-9c0-2.5 3.5-3 3.5-4.5ZM14.5 13l-5 6m0-5.5h.01m4.99 5h.01");
}

</style>
