<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlekvd6wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bill-passed" /></template>
<style>
.vlekvd6wh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.3 21.5H4.5v-19h14v7.8M8 7h7m-7 4h7m-7 4h3m4.391 1.116l2.475-2.475l4.243 4.243l-2.475 2.475ZM18.75 17l-4 4");
}

</style>
