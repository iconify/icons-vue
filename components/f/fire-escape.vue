<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcqx2abwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fire-escape" /></template>
<style>
.pcqx2abwz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 2.5h8.5v19H13ZM3.5 7H13m-9.5 7H13m-9.5 7H13M4.5 7l7.5 7m-7.5 0l7.5 7M3.5 4v17M16 6h.01M19 6h.01M16 11h.01M19 11h.01M16 16h.01M19 16h.01");
}

</style>
