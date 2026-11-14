<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-6decdjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:git-commit-plus" /></template>
<style>
.v-6decdjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10h4.75m0 0a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Zm8.5 0h5.75M18 15v6m-3-3h6");
}

</style>
