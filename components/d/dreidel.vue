<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9cpslo_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dreidel" /></template>
<style>
.n9cpslo_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.723 6.713L18.348 9.56l-1.553 5.795l-7.124 5.338l-3.501-8.185Zm6.606-3.406l-1.294 4.829M6.17 12.508l10.625 2.847");
}

</style>
