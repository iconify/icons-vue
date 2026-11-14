<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh8zdfbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:distort-free" /></template>
<style>
.fh8zdfbhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.288 4.182l4.887-.362m4.964 3.895l1.213 8.009m-3.569 3.573l-6.51-1.085m-4.6-4.967l-.345-4.487M2.5 4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm13.5-1a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM18.5 20a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-15-2.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
