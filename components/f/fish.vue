<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdm0v3bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fish" /></template>
<style>
.qdm0v3bhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 12c2.5-4 5.5-5.5 8-5.5c3.5 0 6 2.5 7 5.5c-1 3-3.5 5.5-7 5.5c-2.5 0-5.5-1.5-8-5.5Zm0 0l-4-4v8ZM17 10.5h.01");
}

</style>
