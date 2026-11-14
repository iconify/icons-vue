<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf2macbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:appetite-loss" /></template>
<style>
.cf2macbvk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.806 19.811A10.5 10.5 0 0 1 12 20.5c-5 0-9-3.25-9-8h5.6m7.8 0H21c0 1.364-.33 2.604-.918 3.679M3.5 3.5l17 17");
}

</style>
