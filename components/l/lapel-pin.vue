<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6g3xubvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lapel-pin" /></template>
<style>
.k6g3xubvn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm1.25 2.75L4 20m2.616-6.152l3.536 3.536l-1.768 1.768l-3.536-3.536Z");
}

</style>
