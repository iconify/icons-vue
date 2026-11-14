<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2xobwbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:liquid-nitrogen-dewar" /></template>
<style>
.z2xobwbqk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5h5V6c0 1 3.5 1.5 3.5 4v9.5a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2V10c0-2.5 3.5-3 3.5-4ZM6 13h12");
}

</style>
