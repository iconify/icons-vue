<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yawz8gx0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:decree" /></template>
<style>
.yawz8gx0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h16V6H4ZM8.4 21H4v-3.5h2.3m11.4 0H20V21h-4.4M6 6v11.5M18 6v11.5m-9-8h6m-6 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
