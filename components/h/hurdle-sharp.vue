<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyhqbbb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hurdle-sharp" /></template>
<style>
.xyhqbbb0h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 5.75h17.5v4H3.25zM8.5 6L7 9.5M13 6l-1.5 3.5m6-3.5L16 9.5m-10.25.25v10.5m12.5-10.5v10.5m-15 0h5m7.5 0h5");
}

</style>
