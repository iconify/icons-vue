<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uy5li62sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-mcp" /></template>
<style>
.uy5li62sa {
  fill: none;
  stroke: var(--svg-color--000, #000);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-7px, 1.7px);
  d: path("m4.4 15l11-11c1.5-1.5 4-1.5 5.5 0s1.5 4 0 5.5l-8.3 8.3m0 0l8.3-8.3c1.5-1.5 4-1.5 5.5 0l.057.057c1.5 1.5 1.5 4 0 5.5l-10 10c-.51.51-.51 1.3 0 1.8l2 2m-.4-22l-8.1 8.1c-1.5 1.5-1.5 4 0 5.5s4 1.5 5.5 0l8.1-8.1");
}

</style>
