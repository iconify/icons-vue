<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5uksnbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:commercial-district" /></template>
<style>
.s5uksnbpa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21v-9H8V3h8.5v5.5h5V21ZM8 12v9m8.5-12.5V21M10.75 7.5h3m-3 4h3m-3 4h3m-8.5-.5v3");
}

</style>
