<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lp36cck-w"/><path class="f5_by-fom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crypto-wallet-check" /></template>
<style>
.f5_by-fom {
  d: path("M20.5 6.75H17a2.25 2.25 0 0 0 0 4.5h3.5M14.75 18l2 2L21 15.75");
}

.lp36cck-w {
  d: path("M12.3 19.5H3.5v-15h17v7.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
