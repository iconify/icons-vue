<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ir0h55dwb"/><path class="nou_9cf9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deep-link" /></template>
<style>
.ir0h55dwb {
  d: path("M7.5 3.6V2.5h12v19h-12V11.4m4.5 7.1h2.6");
}

.nou_9cf9e {
  d: path("m3 3l12 12m0-4.5V15h-4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
