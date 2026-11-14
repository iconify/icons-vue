<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wje33_qqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:archive-box-open" /></template>
<style>
.wje33_qqb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 11.5v7a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-7M2.789 5.093l17.727-3.125l.695 3.939L3.484 9.032ZM4 11.5h16M10 15h4");
}

</style>
