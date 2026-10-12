<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl8mmn0ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:maglev" /></template>
<style>
.kl8mmn0ca {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 8H13c3.5 0 6.6 2.2 8 5a.75.75 0 0 1-.7 1H3.75a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1m1.75 2.75h9M7 17.25h1.5m7 0H17m-14 3h18");
}

</style>
