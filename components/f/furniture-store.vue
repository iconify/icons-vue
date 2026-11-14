<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq2_7u61f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:furniture-store" /></template>
<style>
.hq2_7u61f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0M6.5 15v-2A1.5 1.5 0 0 1 8 11.5h8a1.5 1.5 0 0 1 1.5 1.5v2m-14 0H7v4.5H3.5ZM17 15h3.5v4.5H17ZM7 17h10M5.25 19.5v2m13.5-2v2");
}

</style>
