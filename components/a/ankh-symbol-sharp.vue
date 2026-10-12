<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsjneud0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ankh-symbol-sharp" /></template>
<style>
.qsjneud0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11.75c-2.5-1.5-4-3.5-4-5.5a4 3.5 0 0 1 8 0c0 2-1.5 4-4 5.5Zm-8.25.5h16.5m-8.9 0h1.9l.07.6l.86 7.8l.07.6h-4.5l.07-.6l.86-7.8l.07-.6z");
}

</style>
