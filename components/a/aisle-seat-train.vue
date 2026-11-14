<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4jc0768d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aisle-seat-train" /></template>
<style>
.q4jc0768d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5h9v3.75h-9ZM6.5 15v-4a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v4m-13 0h15v3.5h-15ZM7 18.5v3m10-3v3");
}

</style>
