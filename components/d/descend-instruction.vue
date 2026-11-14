<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5pd6sbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:descend-instruction" /></template>
<style>
.x5pd6sbaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h5v19H4ZM4 7h2.25M4 12h2.25M4 17h2.25M16 3.5v17m-3.75-3.75L16 20.5l3.75-3.75");
}

</style>
