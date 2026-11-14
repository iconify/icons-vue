<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3_cdrzsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:divot-tool" /></template>
<style>
.n3_cdrzsi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.525 10.939l3.536 3.536l-6.364 6.364l-3.536-3.536Zm7.778-7.071l-5.657 5.657m8.486-2.828l-5.657 5.657m-2.829-2.829l2.829 2.829m-1.414-1.415l-1.768 1.768");
}

</style>
