<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdx-9-bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:birthday-offer" /></template>
<style>
.gdx-9-bsp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 11h15v9.5h-15Zm7.5 0V7m0 0c-1.5 0-1.5-2 0-3.5C13.5 5 13.5 7 12 7Zm-7.5 8h15");
}

</style>
