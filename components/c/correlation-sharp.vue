<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l078s3bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:correlation-sharp" /></template>
<style>
.l078s3bdc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h4.5v4.5h-4.5zm0 7h4.5v4.5h-4.5zm7 0h4.5v4.5h-4.5zm-7 7h4.5v4.5h-4.5zm7 0h4.5v4.5h-4.5zm7 0h4.5v4.5h-4.5z");
}

</style>
