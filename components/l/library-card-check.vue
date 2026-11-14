<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wj8voob3a"/><path class="bc6evqbpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:library-card-check" /></template>
<style>
.bc6evqbpq {
  d: path("M6.5 8.5h4v7l-2-1.5l-2 1.5Zm7 .5H18m-4.5 3.5h3M14.75 18l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wj8voob3a {
  d: path("M11.8 19H2.5V5h19v7.3");
}

</style>
