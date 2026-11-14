<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5it4djsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-gloves-pair" /></template>
<style>
.z5it4djsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21.5v-7l-2.75-2.75A1.6 1.6 0 0 1 5 9.5l.5.5V6a2.5 2.5 0 0 1 5 0v15.5Zm13 0v-7l2.75-2.75A1.6 1.6 0 0 0 19 9.5l-.5.5V6a2.5 2.5 0 0 0-5 0v15.5ZM5.5 18h5m3 0h5");
}

</style>
