<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o67356_om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calligraphy-brush-ink" /></template>
<style>
.o67356_om {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.01 3.161l2.829 2.829l-7.071 7.071l-2.829-2.829Zm-7.071 7.071l2.829 2.829L4.99 18.01ZM16 13.5s-2.5 3-2.5 4.5a2.5 2.5 0 0 0 5 0c0-1.5-2.5-4.5-2.5-4.5Z");
}

</style>
