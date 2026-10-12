<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f92v-10ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-ridgeline-sharp" /></template>
<style>
.f92v-10ws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.25h3.5c2 0 2.5-5.5 5-5.5s3 5.5 5 5.5h5m-18.5 6h7c2 0 2.5-5 4.75-5s2.75 5 4.75 5h2m-18.5 6h2c2 0 2.25-3.5 4.5-3.5s2.75 3.5 4.75 3.5h7.25");
}

</style>
