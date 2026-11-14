<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9juooz1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:find-next" /></template>
<style>
.l9juooz1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Zm10.25 4.25l1.75 1.75m2.5-1V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>
