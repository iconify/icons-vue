<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2l4pg9da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:firework-rocket-launch" /></template>
<style>
.l2l4pg9da {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15 9l-3 1l-3.5 3.5l2 2L14 12Zm-5.5 5.5L3 21m1.5-5.5h.01m3.99 5h.01M18.5 4V2M20 5.5h2m-2.5-1L21 3m-3.5 1.5L16 3m3.5 3.5L21 8");
}

</style>
