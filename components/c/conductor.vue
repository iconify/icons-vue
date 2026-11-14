<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjmk36bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:conductor" /></template>
<style>
.zjmk36bbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.641 18.384l4.243-4.243l2.475 2.475l-4.243 4.243ZM8 15.5l12-12m-5.25 15.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0v-5.5m0 0q2.75.75 2.75 3.25");
}

</style>
