<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2a1e3bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hyacinth" /></template>
<style>
.c2a1e3bnh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5a2.25 2.25 0 0 1 2 3a1.75 1.75 0 0 1 0 3.25A1.75 1.75 0 0 1 14 12a2 2 0 0 1-2 3a2 2 0 0 1-2-3a1.75 1.75 0 0 1 0-3.25a1.75 1.75 0 0 1 0-3.25a2.25 2.25 0 0 1 2-3ZM12 15v6.5m0 0c-3.5-1-5-3.5-5-6.75m5 6.75c3.5-1 5-3.5 5-6.75");
}

</style>
