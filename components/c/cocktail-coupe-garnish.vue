<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n8seabbnp"/><path class="nkzbywbql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cocktail-coupe-garnish" /></template>
<style>
.n8seabbnp {
  d: path("M3 5.5h15a7.5 5.5 0 0 1-15 0Zm7.5 5.5v9.5m-4 0h8");
}

.nkzbywbql {
  d: path("M15.5 5.5C16.5 3 21 3 20.5 7c-.25 2-2 2.5-1.5 4.5c.25 1 1.5 1.5 2 1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
