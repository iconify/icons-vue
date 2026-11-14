<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7r5pgr8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:controller-grip" /></template>
<style>
.b7r5pgr8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6.5h10a4 4 0 0 1 4 4l.5 6.5a2.5 2.5 0 0 1-4.5 1.5l-2-3H9l-2 3A2.5 2.5 0 0 1 2.5 17l.5-6.5a4 4 0 0 1 4-4Zm-1.25 5h3M7.25 10v3M16 10.5h.01m2.24 2.25h.01");
}

</style>
