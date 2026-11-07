<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ormh1acmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-import-sharp" /></template>
<style>
.ormh1acmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12V6.444l-4.5-2.222m0 0L12 2L3 6.444v11.112L12 22V10.889M3 6.444l9 4.445l9-4.445M18 15l-3 3l3 3m-3-3h6");
}

</style>
