<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fadesw6tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:curling-iron-sharp" /></template>
<style>
.fadesw6tu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 2.75h4.5v10h-4.5zm0 3.25l4.5-1.5m-4.5 5l4.5-1.5M5.71 4.46l.58-.17l.96-.29v9.25l-.96-.29l-.58-.17l-.96-.29V4.75zM9.75 15h4.5v6.25h-4.5z");
}

</style>
