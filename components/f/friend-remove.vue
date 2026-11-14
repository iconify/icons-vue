<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhqkj0bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:friend-remove" /></template>
<style>
.jhqkj0bdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20c0-2.75 2.1-4.75 4.75-4.75S12 17.25 12 20c0 .6-.4 1-1 1H3.5c-.6 0-1-.4-1-1ZM4.25 7.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm9.75 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM15 18h6");
}

</style>
