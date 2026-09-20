<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="w9km-1pkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:castle-turret-light" /></template>
<style>
.w9km-1pkx {
  fill: currentColor;
  d: path("M216 218h-18V114.49l11.9-11.91a13.9 13.9 0 0 0 4.1-9.89V48a14 14 0 0 0-14-14h-24a6 6 0 0 0-6 6v26h-20V40a6 6 0 0 0-6-6h-32a6 6 0 0 0-6 6v26H86V40a6 6 0 0 0-6-6H56a14 14 0 0 0-14 14v44.69a13.9 13.9 0 0 0 4.1 9.89L58 114.49V218H40a6 6 0 0 0 0 12h176a6 6 0 0 0 0-12M68.24 107.76L54.58 94.1a2 2 0 0 1-.58-1.41V48a2 2 0 0 1 2-2h18v26a6 6 0 0 0 6 6h32a6 6 0 0 0 6-6V46h20v26a6 6 0 0 0 6 6h32a6 6 0 0 0 6-6V46h18a2 2 0 0 1 2 2v44.69a2 2 0 0 1-.58 1.41l-13.66 13.66A6 6 0 0 0 186 112v106h-28v-50a30 30 0 0 0-60 0v50H70V112a6 6 0 0 0-1.76-4.24M146 218h-36v-50a18 18 0 0 1 36 0Z");
}

</style>
