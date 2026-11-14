<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz36g7rzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:game-show" /></template>
<style>
.oz36g7rzg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 21.5V15h15v6.5M12 2l1.5 3.5l3.75.25l-2.75 2.5l.75 3.75L12 10l-3.25 2l.75-3.75l-2.75-2.5l3.75-.25ZM9 18.25h6");
}

</style>
