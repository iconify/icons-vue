<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wso8o2ltg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:labor-law" /></template>
<style>
.wso8o2ltg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.086 3.55l6.364 6.364l-3.536 3.536L8.55 7.086Zm-.336 6.7L4.5 17.5m8.5.5h8v3h-8Z");
}

</style>
