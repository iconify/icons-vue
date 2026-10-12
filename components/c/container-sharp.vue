<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b83rpduwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:container-sharp" /></template>
<style>
.b83rpduwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12h4v4H3zm7 0h4v4h-4zm7 0h4v4h-4zM6.5 5h4v4h-4zm7 0h4v4h-4zM2.75 19.25h18.5");
}

</style>
