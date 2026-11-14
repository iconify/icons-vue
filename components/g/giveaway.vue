<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5au6gwno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:giveaway" /></template>
<style>
.r5au6gwno {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.9 11.5H2.5v-4h17v3.8M12.7 21H4v-9.5h11.9m-4.9-4v6.6m0 2.9v4m0-13.5c-2.5-5-6.5-3-3.5 0m3.5 0c2.5-5 6.5-3 3.5 0m3.25 6.5l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
