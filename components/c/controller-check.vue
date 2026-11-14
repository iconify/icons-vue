<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="za8oh1bbm"/><path class="z2mygabew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:controller-check" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z2mygabew {
  d: path("M14.75 10a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm0 8l2 2L21 15.75");
}

.za8oh1bbm {
  d: path("M13.283 15.5H8c-.75 1.25-1.5 2-2.75 2c-1.5 0-2.75-1.25-2.75-3V10c0-3.25 2-5.5 5-5.5h9c3 0 5 2.25 5 5.5v2.273M5.5 10H9M7.25 8.25v3.5");
}

</style>
