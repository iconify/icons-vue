<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnfmvqbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:inventory-shelves" /></template>
<style>
.fnfmvqbed {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.75v18.5m16-18.5v18.5M4 8h16M4 14h16M4 20h16M7 14v-2a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v2m0 6v-2a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v2");
}

</style>
