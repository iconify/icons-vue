<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wojyevv_d"/><path class="lnxfo0wli"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lemon-water" /></template>
<style>
.lnxfo0wli {
  d: path("M7.5 14.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3-3v6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wojyevv_d {
  d: path("M3 3h13.5v16a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V6.5Zm13.5 3H18a2.5 2.5 0 0 1 2.5 2.5V13a2.5 2.5 0 0 1-2.5 2.5h-1.5m-12-7h12");
}

</style>
