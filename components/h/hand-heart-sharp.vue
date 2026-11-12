<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-q8ppb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-heart-sharp" /></template>
<style>
.n-q8ppb6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 16l3-3c.6-.6 1.2-1 2-1h3a2 2 0 1 1 0 4h-2m4-2l3-3a2.121 2.121 0 1 1 3 3l-5 5c-.64.64-1.36 1-2 1H8m-5-5l6 6m3-17c-2-2-5 0-3 2l3 3l3-3c2-2-1-4-3-2");
}

</style>
