<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beo5g3kfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:holy-water-sharp" /></template>
<style>
.beo5g3kfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.75h4v3.5l2.75 3.5l.75.9v10.6h-11v-10.6l.75-.9L10 6.25Zm0 2.5h4m-2 7v5.5m-2-3.5h4");
}

</style>
