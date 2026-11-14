<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obf6680my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:birthday-cake-slice" /></template>
<style>
.obf6680my {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.849 14.183l13.5-3.177A1.75 1.75 0 0 1 20.5 12.71v6.04a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75v-2.864a1.75 1.75 0 0 1 1.349-1.703M3.5 17.5l17-2.25m-3.75-3.75V7.25m0-2.75h.01");
}

</style>
