<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8hc43bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cable-split" /></template>
<style>
.b8hc43bvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5h4V7h-4Zm13 0h4V7h-4ZM5.5 7v1c0 3 6.5 2.5 6.5 6v2.5M18.5 7v1c0 3-6.5 2.5-6.5 6m-2 2.5h4v5h-4Z");
}

</style>
