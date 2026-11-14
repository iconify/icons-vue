<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-yi6gb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:herb-planter" /></template>
<style>
.f-yi6gb7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12.5h14a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 14A1.5 1.5 0 0 1 5 12.5m1.797 3h10.406a1.5 1.5 0 0 1 1.475 1.768l-.454 2.5A1.5 1.5 0 0 1 16.748 21H7.252a1.5 1.5 0 0 1-1.476-1.232l-.454-2.5A1.5 1.5 0 0 1 6.797 15.5M8 12.5v-4c0-3-2-5-4.5-5c0 3 2 5 4.5 5m8 4v-4c0-3 2-5 4.5-5c0 3-2 5-4.5 5");
}

</style>
