<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpifnqb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:faucet-touchless" /></template>
<style>
.hpifnqb2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.5h8A4.5 4.5 0 0 1 16 12v1.5m-8-6v-3m-2.5 0h5m8.531 7.25a3.5 3.5 0 0 1 0 3.5m2.165-4.75a6 6 0 0 1 0 6");
}

</style>
