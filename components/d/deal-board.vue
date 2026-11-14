<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-xp7nb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deal-board" /></template>
<style>
.k-xp7nb4p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3H7m2.75 0h4.5M17 3h4.5m-19 3.5H7V11H2.5Zm0 7.25H7V21H2.5ZM9.75 6.5h4.5v9h-4.5Zm7.25 0h4.5V13H17Zm0 9.25h4.5v3.75H17Z");
}

</style>
