<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty34-1bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:humidity-control" /></template>
<style>
.ty34-1bpw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5s-6.5 6.5-6.5 11a6.5 6.5 0 0 0 13 0c0-4.5-6.5-11-6.5-11ZM9.5 15h5");
}

</style>
