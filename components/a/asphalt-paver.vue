<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d71a8esjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:asphalt-paver" /></template>
<style>
.d71a8esjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8H16v6.5H7.5ZM16 3.5v11h2.5l3-11M8 14.5h6v4H8ZM7.5 11H4v4.5m-1.5 0h3v3h-3Zm0 6h19");
}

</style>
