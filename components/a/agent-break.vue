<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_ezg8b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:agent-break" /></template>
<style>
.r_ezg8b3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.2 17H3V5.5h15v7.2M10.5 2.5v3m-3 5.5h.01m5.99 0h.01M15 15.5h4.5v4A1.5 1.5 0 0 1 18 21h-1.5a1.5 1.5 0 0 1-1.5-1.5Zm4.5 1h.75a1.5 1.5 0 0 1 0 3h-.75");
}

</style>
