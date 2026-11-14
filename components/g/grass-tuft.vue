<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo84kjcfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grass-tuft" /></template>
<style>
.vo84kjcfz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 20.5C12 14 12.5 8 15 3m-3 17.5Q10.5 10.75 4.5 7M12 20.5c1-5 4-8.5 8-10m-14 10h12");
}

</style>
