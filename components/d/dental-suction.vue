<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewol5pbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-suction" /></template>
<style>
.ewol5pbmk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 21.5v-11A4.5 4.5 0 0 1 9 6h3.5m0-1.25l7-2.25v7l-7-2.25ZM17 12.5C16 14 15 15 15 16a2 2 0 0 0 4 0c0-1-1-2-2-3.5Z");
}

</style>
