<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3vq9-p7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:center-of-gravity" /></template>
<style>
.e3vq9-p7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10h19m-10.827 2.522l-2.516 4.779A1.5 1.5 0 0 0 9.485 19.5h5.03a1.5 1.5 0 0 0 1.328-2.199l-2.516-4.779a1.5 1.5 0 0 0-2.654 0M12 5h.01");
}

</style>
