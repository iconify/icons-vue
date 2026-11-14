<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7787tb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-breed-terrier" /></template>
<style>
.h7787tb7f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 10h8l.25-5.25l1.25-2l1 2h1L21.5 7v2.5l-3.5.75l-.5 4.75h-13v-4L3 5.75L5.25 10ZM6 15v5.5M9 15v5.5m4.5-5.5v5.5m3-5.5v5.5m1.25-13h.01");
}

</style>
