<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v88eoebqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-fire-blanket" /></template>
<style>
.v88eoebqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h18v7q-2.25 1.5-4.5 0t-4.5 0t-4.5 0t-4.5 0Zm8 11.25c.25 2-2.5 2.5-2.5 4.5a3.5 3.25 0 0 0 7 0c0-1.5-1-2.5-1.75-3.25c-.25 1-.75 1.5-1.25 1.75q.375-1.875-1.5-3ZM3 6h18");
}

</style>
