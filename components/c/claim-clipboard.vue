<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wkkrz2b6r"/><path class="zae_0fwhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:claim-clipboard" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wkkrz2b6r {
  d: path("M8.5 4h-2a2 2 0 0 0-2 2v13.5a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2h-2");
}

.zae_0fwhj {
  d: path("M8.5 2.5h7V6h-7Zm0 11L11 16l4.5-5");
}

</style>
