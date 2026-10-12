<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5ko51b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bat-halloween-sharp" /></template>
<style>
.f5ko51b3m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3.05a3.75 3.75 0 1 0 2.75 4.6a3 3 0 0 1-2.75-4.6Zm3.5 10.7l1-1.5l.5 1.5c1.75-1 4.5-1.5 7.75-.5l-1.75 1.4v2.6l-1.714-1.286L16.25 17.5l-1.406-.937L14 18.25l-2 2l-2-2l-.844-1.687l-1.406.937l-1.536-1.536L4.5 17.25v-2.6l-1.75-1.4c3.25-1 6-.5 7.75.5l.5-1.5Z");
}

</style>
