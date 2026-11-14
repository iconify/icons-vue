<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-g7lsbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leave-policy" /></template>
<style>
.l-g7lsbwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 12.5v-10h14v7.1m0 10.3v1.6h-7.8M7.5 6h.01M11 6h.01m3.49 0h.01M7.5 9.25h.01m3.49 0h.01m2.74-.75l1.5 1.5m0-1.5l-1.5 1.5M2.24 15.774l18.585-3.95l.935 4.402l-18.585 3.95Zm3.423-.727l.416 1.956m2.519-2.58l.312 1.467m2.622-2.091l.416 1.956m2.519-2.58l.312 1.468m2.622-2.091l.416 1.956");
}

</style>
