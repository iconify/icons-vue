<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hvr4jbcps"/><path class="lnqvuebja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cloud-moon-rain" /></template>
<style>
.hvr4jbcps {
  d: path("M6.5 14.75a3.25 3.25 0 0 1 0-6.5a4.5 4.5 0 0 1 8.75.75a2.75 2.75 0 0 1-.75 5.75ZM17.196 2.049a5 5 0 0 1 3.078 8.231");
}

.lnqvuebja {
  d: path("M17.146 2.048a4.5 4.5 0 0 1 .614 4.995M7.5 18l-1 2.5m5-2.5l-1 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
