<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6a258bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:book-audio-sharp" /></template>
<style>
.i6a258bki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 18.75v-16h14.5v13.5H4.75v2Zm0 0v2.5h14.5v-4.5M9 8.25v3.5m3-5.25v7m3-5.25v3.5");
}

</style>
