<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw0gnv4hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:container-terminal" /></template>
<style>
.tw0gnv4hy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5h18M4.5 15h6v5.5h-6Zm6.5 0h6v5.5h-6ZM7.5 9.5h6V15h-6Zm9.5-5V12h3");
}

</style>
