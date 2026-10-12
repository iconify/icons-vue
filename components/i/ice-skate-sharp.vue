<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0defz-on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ice-skate-sharp" /></template>
<style>
.e0defz-on {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 4.25v-1h6v6.5l4.5 1.75l2.495 1.009l.005 2.691v2.55h-13v-1ZM8 6.75h2m-2 3h2m-2.25 7v3.5m8.25-3.5v3.5m-12.25 0h17v-2.5");
}

</style>
