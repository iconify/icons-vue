<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwk7sbbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hand-grip" /></template>
<style>
.zwk7sbbqw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 18.5V7a1.75 1.75 0 0 1 3.5 0a1.75 1.75 0 0 1 3.5 0a1.75 1.75 0 0 1 3.5 0v9a2.5 2.5 0 0 1-2.5 2.5Zm0-9H4A1.75 1.75 0 0 0 4 13h2.75m10.5-3.5H20a1.75 1.75 0 0 1 0 3.5h-2.75m-7-6v2.5m3.5-2.5v2.5m-7 6.25h5.75");
}

</style>
