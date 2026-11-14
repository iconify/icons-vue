<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw-6p-byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:floor-level" /></template>
<style>
.iw-6p-byn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 21.5v-13L15 3l6.5 5.5v13Zm0-13h13M8.5 15h13M12 11.75h.01m2.99 0h.01m2.99 0h.01M2.5 9l3 2.75l-3 2.75");
}

</style>
