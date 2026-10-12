<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrtv2dolw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:electric-guitar-sharp" /></template>
<style>
.mrtv2dolw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.96 9.76l.51-1.54l.38-1.14l.16 1.19l.25 1.86l.15 1.19l.85.85l.57.57l.85.85l1.18.21l.75.14l1.18.21l-.96.73l-1.62 1.23l-.96.73l-.63 1.02l-1 1.63l-.63 1.03H6.6l-.85-.85l-1.42-1.42l-.85-.85v-3.39l1.08-.54l.68-.34q1.07-.53 2.03-1.25l.35-.26l.96-.72zm7.68-2.96l.63.63l.43.43l.42-.43l1.27-1.27l.43-.42l-.43-.43l-.63-.63l-.43-.43l-.42.43l-1.27 1.27l-.43.42zm-5.09 5.65l5.51-5.51m-9.05 6.22l2.83 2.83M6.17 15L9 17.83");
}

</style>
